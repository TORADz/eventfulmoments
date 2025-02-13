<script setup>
import { RouterLink } from 'vue-router';
</script>
<template>
   <main class="flex justify-between items-center px-[100px] py-[33px] bg-[#008289] text-white font-(family-name:--bodyfont)  shrink md:shrink-0 ">
    <RouterLink to="/" ><i class="">Eventful Moments.</i></RouterLink> 
    <div class=" flex justify-between w-[15%] ">
        <div class="hover:border hover:border-solid hover:border-white py-[10px] px-[30px] ">
            <RouterLink to="/" >Login</RouterLink>
        </div>
        <div class="hover:border hover:border-solid hover:border-white py-[10px] px-[30px] ">
            <RouterLink to="/register">Register</RouterLink>
        </div>
    </div>
   </main> 
</template>