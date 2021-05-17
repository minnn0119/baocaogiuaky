<template>
  <div id="app-3">
    <button v-on:click='seen = ! seen'> Ẩn/hiện</button>
  <span v-if="seen">Thoắt ẩn thoắt hiện</span>
</div>
</template>

<script>
export default {
     data(){
       return{
    seen: true
       }
  }
}

</script>


<style>
#app-3 {
  font-size: 20px;
  margin: 40px 0 0;
 color: #006666;

}
</style>
