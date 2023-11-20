<script setup>
import { RouterView} from 'vue-router'
import Nav from './components/Nav.vue'
import { ref } from 'vue'

const randomState = ref("")
</script>

<template>{{ randomState }}
  <header>
    <div>
      <button @click="randomState = 'Hello World'">Random button</button>
      <Nav/>
        <RouterView/>
    </div>
  </header>
  </template>