<template>
    <ul class="checkbox-list">
      <li v-for="item in items" :key="item.value">
        <el-checkbox v-model="item.checked">{{ item.label }}</el-checkbox>
      </li>
    </ul>
    <el-input v-model="input" style="width: 240px" placeholder="Please input" />
  </template>
  
  <script>
  import { ref } from 'vue'
  
  export default {
    name: 'TodoList',
    setup() {
      const input = ref('')
      const items = ref([
        { label: 'Option 1', value: 'option1', checked: false },
        { label: 'Option 2', value: 'option2', checked: false },
        { label: 'Option 3', value: 'option3', checked: false }
      ]);
  
      return {
        input,
        items,
      }
    }
  }
  </script>
  
  <style scoped>
  .checkbox-list {
    list-style: none;
    padding: 0;
  }
  
  .checkbox-list li {
    margin-bottom: 10px;
  }
  </style>
  