<template>
  <div class="h">hellow world</div>
  <button @click="add">add</button> {{ num }}
</template>

<script lang="ts" setup>
import { ref } from "@vue/reactivity";

let num = ref(1);
const add = () => {
  num.value += 1;
};
</script>
