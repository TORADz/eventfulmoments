<script setup>
import { RouterLink } from 'vue-router';

</script>

<template>
    <main class="font-(family-name:--bodyfont) mt-[3%]">
      <div class="flex justify-around gap-[40%]">
        <div>
        <h1 class="font-(--fontbold) text-[25px]">Welcome John Doe,</h1>
        <p class="text-[12px]">Here are items in your eventful moment bucket.</p>
      </div>

      <RouterLink to="/item">
        <button class=" bg-[#5271FF] text-white py-[15px] px-[60px] text-[12px] rounded-[10px] hover:bg-black">Add Item</button>
      </RouterLink>

      </div>
      
     <div class="grid grid-cols-2 gap-6 h-[600px] p-[70px] ">
    <div class="border-solid rounded-[8px] shadow-black inset-shadow-2xs shadow-sm">
        <div class="p-[25px]">
            <h2 class="font-bold">Lorem ipsum began as scrambled, nonsensical Latin derived from Cicero’s 1st-century BC text De Finibus Bonorum et Malorum.</h2>
            <p class="text-[12px] pt-[20px]">Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real. Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real.</p>
        </div>
        <div class="flex justify-around text-[10px] gap-[50%]">
            <h6 class="text-[#5271FF]">View Details</h6>
            <div class="flex gap-[20px] mb-[20px]">
                <h6 class="text-[#B2B2B2]">20/05/2021</h6>
                <h6>20/05/2021</h6>
            </div>
        </div>
    </div>
      <div class="border-solid rounded-[8px] shadow-black inset-shadow-2xs shadow-sm">
        <div class="p-[25px]">
            <h2 class="font-bold">Lorem ipsum began as scrambled, nonsensical Latin derived from Cicero’s 1st-century BC text De Finibus Bonorum et Malorum.</h2>
            <p class="text-[12px] pt-[20px]">Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real. Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real.</p>
        </div>
        <div class="flex justify-around text-[10px] gap-[50%]">
            <h6 class="text-[#5271FF]">View Details</h6>
            <div class="flex gap-[20px] mb-[20px]">
                <h6 class="text-[#B2B2B2]">20/05/2021</h6>
                <h6>20/05/2021</h6>
            </div>
        </div>
      </div>
      <div class="border-solid rounded-[8px] shadow-black inset-shadow-2xs shadow-sm">
        <div class="p-[25px]">
            <h2 class="font-bold">Lorem ipsum began as scrambled, nonsensical Latin derived from Cicero’s 1st-century BC text De Finibus Bonorum et Malorum.</h2>
            <p class="text-[12px] pt-[20px]">Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real. Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real.</p>
        </div>
        <div class="flex justify-around text-[10px] gap-[50%]">
            <h6 class="text-[#5271FF]">View Details</h6>
            <div class="flex gap-[20px] mb-[20px]">
                <h6 class="text-[#B2B2B2]">20/05/2021</h6>
                <h6>20/05/2021</h6>
            </div>
        </div>
      </div>
      <div class="border-solid rounded-[8px] shadow-black inset-shadow-2xs shadow-sm">
        <div class="p-[25px]">
            <h2 class="font-bold">Lorem ipsum began as scrambled, nonsensical Latin derived from Cicero’s 1st-century BC text De Finibus Bonorum et Malorum.</h2>
            <p class="text-[12px] pt-[20px]">Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real. Until recently, the prevailing view assumed lorem ipsum was born as a nonsense text. “It’s not Latin, though it looks like it, and it actually says nothing,” Before & After magazine answered a curious reader, “Its ‘words’ loosely approximate the frequency with which letters occur in English, which is why at a glance it looks pretty real.</p>
        </div>
        <div class="flex justify-around text-[10px] gap-[50%]">
            <h6 class="text-[#5271FF]">View Details</h6>
            <div class="flex gap-[20px] mb-20px">
                <h6 class="text-[#B2B2B2]">20/05/2021</h6>
                <h6>20/05/2021</h6>
            </div>
        </div>
      </div>
     </div>

     <div class="flex justify-center mt-[150px]">
      <button class=" bg-[#5271FF] text-white py-[15px] px-[60px] text-[12px] rounded-[10px] hover:bg-black">Load More</button>
     </div>
    </main>
</template>