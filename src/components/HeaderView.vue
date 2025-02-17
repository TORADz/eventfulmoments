<script setup>
import { RouterLink } from 'vue-router';
</script>
<template>
   <main class="flex justify-between items-center px-[5%] py-[33px] bg-[#008289] text-white font-(family-name:--bodyfont)  shrink md:shrink-0 ">
    <RouterLink to="/" ><i class="">Eventful Moments.</i></RouterLink> 
    <div class=" flex justify-between w-[30%] md:w-[10%] text-center sm:text-left">
        <div class="hover:border hover:border-solid hover:border-white py-[10px] ">
            <RouterLink to="/" >Login</RouterLink>
        </div>
        <div class="hover:border hover:border-solid hover:border-white py-[10px] ml-[10px]">
            <RouterLink  to="/register">Register</RouterLink>
        </div>
    </div>
   </main> 
</template>