<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
    title: String,
    image: String,
    slogan: String,
    description: String,
    tag: String
})
</script>

<template>
    <div class="aspect-video relative rounded-md overflow-hidden">
        <img v-if="props.image" :src="props.image" class="h-full w-full object-cover">
        <div class="flex flex-col items-start p-2 h-full w-full absolute top-0 left-0 bg-gray-900 bg-opacity-50">
            <div class="leading-none text-xl mb-2">{{ props.title }}</div>
            <div v-if="props.slogan" class="mb-2 text-base">{{ props.slogan }}</div>
            <div v-if="props.description" class="text-sm">{{ props.description }}</div>
            <div v-if="props.tag" class="flex-1 flex flex-col justify-end">
                <div
                    class="justify-self-end text-xs w-min-content px-3 py-1 rounded-full bg-zinc-900 bg-opacity-40 text-white">
                    {{
                        props.tag }}
                </div>
            </div>
        </div>
    </div>
</template>
