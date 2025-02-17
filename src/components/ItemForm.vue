<script setup> 
import { RouterLink } from "vue-router";

</script>

<template>
 <main class="flex justify-between items-center w-[50%] h-[100%] pt-[5%] pl-[5%] font-(family-name:--bodyfont) shrink sm:text-center">
       
        <form class="w-[60%] " action="">
            <label class="text-[12px]" for="Email">Date in the future</label> 
            <br>
            <input class="w-full p-[10px] border-solid border-[1px] rounded-[7px] mb-[15px]" type="text" id="Date"> 
            <br>
            <label class="text-[12px]" for="Email">Title</label> 
            <br>
            <input class="w-full p-[10px] border-solid border-[1px] rounded-[7px] mb-[15px]" type="text" id="Title"> 
            <br>
            <label class="text-[12px]" for="Password">Details</label>
            <br>
            <textarea class="w-full h-[100%] p-[10px]  border-solid border-[1px] rounded-[7px]" type="text" id="text">
            </textarea>
            <br>
            <RouterLink  to="/welcome" class=" flex justify-center mt-[30px]">
                <button class=" bg-[#5271FF] text-white py-[15px] px-[70px] text-[12px] rounded-[10px] hover:bg-black">Save</button>
            </RouterLink>
           
        </form>
    </main>

</template>