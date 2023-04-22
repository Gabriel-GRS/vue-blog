<template>
    <div class="bg-white h-auto w-[340px] sm:w-[38vw] rounded-md">
        <header class="flex justify-between p-4 sm:p-6">
            <p class="text-[#717171]">{{ props.data }}</p>
            <img class="h-4 w-4" src="../assets/icons/hearth.png" alt="">
        </header>
        <section>
            <div class="flex gap-2 flex-col p-4">
                <h1 class="text-[#1A202C] font-medium text-xl sm:text-2xl">{{ props.title }}</h1>
                <p class="text-[#717171]">{{ props.text }}
                </p>
            </div>
        </section>
    </div>
</template>

<script setup lang="ts">
const props = defineProps<{
    title: string,
    data: string,
    text: string
}>();
</script>
