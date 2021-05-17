<template>
  <div id="app-5">
  <p>{{ message }}</p>
  <button v-on:click="reverseMessage">Đảo ngược câu nào</button>
</div>
</template>

<script>
export default {
      data() {
        return{
    message: 'qua lại khách chờ sông lặng sóng'
  }},
  methods: {
    reverseMessage: function () {
      this.message = this.message.split(' ').reverse().join(' ')
    }
  }
}

</script>


<style>
#app-5 {
  font-size: 20px;
  margin: 40px 0 0;
  color: #006666;

}
</style>

