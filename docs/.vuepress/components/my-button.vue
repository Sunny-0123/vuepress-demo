<template>
  <button @click="handleClick">我是一个按钮</button>
</template>

<script>
export default {
  name: "my-button",
  methods:{
    handleClick(){
      console.log("我是一个按钮111")
    }
  }
}
</script>

<style scoped>

</style>
