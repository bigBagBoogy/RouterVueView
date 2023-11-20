<script setup>
import { RouterView} from 'vue-router'
import Nav from './components/Nav.vue'


</script>

<template>
  <header>
    <div>
      <Nav/>
        <RouterView/>
    </div>
  </header>
  </template>