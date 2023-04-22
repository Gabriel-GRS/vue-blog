<template>
    <div class="bg-white h-auto w-[340px] rounded-md">
        <header class="flex justify-between p-4">
            <p class="text-[#717171]">{{ props.data }}</p>
            <img class="h-4 w-4" src="../assets/icons/hearth.png" alt="">
        </header>
        <section>
            <div class="flex flex-col p-4 ">
                <h1 class="text-[#1A202C] font-medium text-lg">{{ props.title }}</h1>
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
