<template>
    <div class="relative">
        <input
            class="w-[90vw] h-[35px] pl-12 outline-none text-white placeholder:text-[#ffffff33] rounded-md bg-[#ffffff33]"
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
