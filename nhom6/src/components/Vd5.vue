<template>
  <div id="app-6">
  <p>{{ message }}</p>
  <input v-model="message">
</div>
</template>

<script>
export default {
     data() {
       return{
    message: 'Hãy sửa thông điệp này'
  }
     }
}

</script>


<style>
#app-6 {
  font-size: 20px;
  margin: 40px 0 0;
  color: #42b983;

}
</style>
