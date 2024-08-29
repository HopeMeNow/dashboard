<template>
	<div class="common-layout">
    <el-container>
      <el-header>Good morning, me!</el-header>
      <el-main>
        <el-row :gutter="20">
          <el-col :span="12"><div class="grid-content">Погода</div></el-col>
          <el-col :span="6"><div class="grid-content">Курс доллара</div></el-col>
          <el-col :span="6"><div class="grid-content">Время</div></el-col>
        </el-row>
        <el-row>
          <el-col :span="24"><div class="grid-content"><TodoList/></div></el-col>
        </el-row>
      </el-main>
    </el-container>
  </div>
</template>
  
<script>
  import TodoList from './TodoList.vue'

	export default {
		name: 'MainTemplate',
    components: {
      TodoList,
    }
	}
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.el-row {
		margin-bottom: 20px;
	}

	.grid-content {
		min-height: 36px;
    text-align: left;
	}

  .el-header {
    color: black;
    text-align: left;
    height: auto;
    font-size: 76px;
    margin-top: 24px;
  }

  .common-layout {
    position: relative;
    z-index: 2;
  }
</style>
  