<template>
  <div id="app-4">
  <ol>
    <li v-for="(todo,min) in todos" :key="min">
      {{ todo.text }}
    </li>
  </ol>
</div>
</template>

<script>
export default {
      data() {
        return{
    todos: [
      { text: 'Học JavaScript' },
      { text: 'Học Vue' },
      { text: 'Xây dựng cái gì đó hay ho' }
    ]
        }
  }
}

</script>


<style>
#app-4 {
  font-size: 20px;
  margin: 40px 0 0;
  color: #42b983;
 
}
</style>
