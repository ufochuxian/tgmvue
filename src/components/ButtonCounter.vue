<template>

  <div id="example">
    <my-component></my-component>
  </div>

</template>

<script>
import Vue from "vue";

export default {
name: "ButtonCounter"
}

Vue.component('my-component',{
  template: '<button v-on:click="count++">you clicked me {{counter}}} times.</button>',
  data: function () {
    return {
      counter:0
    }
  }
})

new Vue({
  el: '#example',
  data : {

  }
})

</script>

<style scoped>

</style>