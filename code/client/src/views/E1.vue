<template>
<h1 class="ref"></h1>
  <h1 class="reactive"></h1>
</template>

<script>
import {ref , reactive } from "vue";
const msg = ref("Hello world !!")
const User = reactive({name : "xulianjiang"})
export default {
  name: "E1"
}
</script>

<style scoped>
.ref  {
  color: red;
}
.reactive {
  color: deepskyblue;
}
</style>