<template>
  <div  class="wrap-input">
<!--     <label >Start time: </label>
    <input type="time"  value="12:23" disabled>
    <label > End time: </label>
    <input type="time" value="16:12" disabled> -->
  </div>
</template>

<script>
export default {
  methods:{
    checkQuestion(){
      let error = false
      let msg = ""
      return {"error":error,"msg":msg};
    }
  }
}
</script>

<style lang="scss" scoped>
 .wrap-input{
    display: flex;
  }
</style>