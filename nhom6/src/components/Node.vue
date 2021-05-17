<template>
  <div id="node">
   <input type="text" v-model="newTask">
   <button v-on:click="task.push({content: newTask, done: false })">Thêm Task</button>
   <div v-for="(task,minh) in task" :key="minh" >
     <input type="checkbox" v-model="task.done">
     <span :class="{done: task.done}">{{ task.content }}</span>
   </div>
  </div>
</template>

<script>

export default {

  data(){
    return{
      newTask:'',
      task:[]
    }
  }

  }
</script>

<style>
#node{
  font-size: 20px;
  color: #006666;
}
.done{

  text-decoration: line-through;
}
</style>
