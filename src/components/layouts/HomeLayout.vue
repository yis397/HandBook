<script  setup lang="ts">
import { defineComponent } from '@vue/runtime-core'
import NavBar from '../NavBar.vue'


</script>

<template lang="">
    <div class="grid grid-cols-4 ">
        <div class="nav col-span-1">
             <NavBar/>
        </div>
       <div class="col-span-2 bg-slate-200">
            <p>hola mundo</p>
            
        </div>
        <div class="col-span-1 bg-slate-500">
            <p>hola mundo</p>
            
        </div>
    </div>
</template>

<style scoped>
    .nav{
        height: 100vh;

    }
</style>