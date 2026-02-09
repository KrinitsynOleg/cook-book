
<template>


  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>
<button @click="test()">test</button>
</template>

<script setup>
import { ref } from 'vue'



const count = ref(0)
function test(){
  console.log(count.value)
}
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
