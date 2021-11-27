<template>
  <div>
    Count:{{store.$state.count}}
    <button @click="store.increment()">Hit me</button> 
 
   
  </div>
</template>
<script setup>
import {useStore} from '@/store'
const store=useStore();
</script>