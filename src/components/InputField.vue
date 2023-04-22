<template>
    <div class="relative">
        <input
            class=" w-[90vw] sm:w-[38vw] h-[35px] sm:h-[40px] pl-12  text-white placeholder:text-[#ffffff33] rounded-md bg-[#ffffff33] focus:outline-dashed outline-[#574AE8] outline-2 ease-out duration-100 outline-offset-2"
            type="text" placeholder="Pesquisar no blog">
        <div class="absolute top-[25%] left-[10px]">
            <img class="h-[20px]" src="../assets/icons/vector.png" alt="">
        </div>
    </div>
</template>

<script setup lang="ts">
const props = defineProps<{
    imagePath: string
}>();
</script>
