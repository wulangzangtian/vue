<script setup lang="ts">
import {ref} from "vue"
let msg = ref("hello")

function change(){
  msg.value = "word"
}
</script>
<template>
  <h1>{{msg}}</h1>
  <input type="button" value="修改msg" @click="change">
</template>
<style>

</style>
