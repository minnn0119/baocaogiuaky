<template>
  <div id="app-2">
  <span v-bind:title="message">
    Rê chuột lên đây một vài giây để xem thuộc tính `title` được bind!
  </span>
</div>
</template>

<script>
export default {
    data() {
      return{
    message: 'Bạn đã mở trang này vào ' + new Date().toLocaleString()
  }
}
}

</script>


<style>
#app-2 {
  font-size: 20px;
  margin: 40px 0 0;
  color: #42b983;

}
</style>
