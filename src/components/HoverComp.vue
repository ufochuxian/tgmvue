<template>

  <div>

    <h1>{{ message }}</h1>
    <span v-bind:title="message">

      鼠标悬停几秒钟查看此处动态绑定的提示信息!

    </span>

  </div>

</template>

<script>
export default {
  name: "HoverComp",
  props: {
    message: String
  }
}
</script>

<style scoped>

</style>