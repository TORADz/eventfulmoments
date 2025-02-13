<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <main class="flex justify-center items-center w-screen h-[80%] pt-[8%] font-(family-name:--bodyfont) shrink md:shrink-0">
       <div class="w-[30%] ">
        <h1 class="text-(length:--heading1) font-(--fontbold)">Welcome Back,</h1>
        <p class="py-[5%]">Hi, my name is Eventful Moments, I am a bucket… no, not the bucket of water but I store awesome moments you will like to have in coming years.</p>
        <form action="">
            <label class="text-[12px]" for="Email">Email</label> 
            <br>
            <input class="w-full p-[10px] border-solid border-[1px] rounded-[7px] mb-[15px]" type="text" id="Email "> 
            <br>
            <label class="text-[12px]" for="Password">Password</label>
            <br>
            <input class="w-full p-[10px] border-solid border-[1px] rounded-[7px]" type="text" id="Password">
            <br>
            <RouterLink to="/welcome"class=" flex justify-center mt-[30px]">
                <button class=" bg-[#5271FF] text-white py-[15px] px-[70px] text-[12px] rounded-[10px] hover:bg-black">Login</button>
            </RouterLink>
           
        </form>
       </div>
    </main>
</template>