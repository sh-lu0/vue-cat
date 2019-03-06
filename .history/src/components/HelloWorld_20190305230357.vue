<template>
   <div>
     {{ msg }}
    <form>
      <button>Add Task</button>
      <button>Delete Finished Tasks</button>
      <p>input: <input type="text"></p>
      <p>task: </p>
    </form>
    <div class="task-list">
      <label class="task-list__item"><input type="checkbox"><button>Edit</button>vue-router</label>
      <label class="task-list__item"><input type="checkbox"><button>Edit</button>vuex</label>
      <label class="task-list__item"><input type="checkbox"><button>Edit</button>vue-loader</label>
      <label class="task-list__item--checked"><input type="checkbox"><button>Edit</button>awesome-vue</label>
    </div>
   </div>
 </template>

<script>
export default {
  name: 'hello',
  data (){
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss" scoped>
@mixin flex-vender() {
  display: flex;
  display: -webkit-flex;
  display: -moz-flex;
  display: -ms-flex;
  display: -o-flex;
}
.task-list {
  
}
</style>
