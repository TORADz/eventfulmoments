<script setup>
import { RouterLink } from 'vue-router';
</script>
<template>
   <main class="flex justify-between items-center px-[100px] py-[33px] bg-[#008289] text-white">
    <i class="">Eventful Moments.</i>
    <div class=" flex justify-between w-[15%]">
        <RouterLink to="/">Login</RouterLink>
        <RouterLink to="/register">Register</RouterLink>
    </div>
   </main> 
</template>