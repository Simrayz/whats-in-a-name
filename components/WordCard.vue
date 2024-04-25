<script setup lang="ts">
import { ref } from 'vue'

const props = defineProps({
    word: String,
    translation: String,
})
</script>

<template>
    <div class="space-y-2 aspect-video relative rounded-md overflow-hidden p-2 bg-zinc-900">
        <div class="text-lg text-zinc-100">🤨 {{ props.word }}</div>
        <div v-click class="text-sm! text-wrap break-word overflow-hidden">Norsk: {{ props.translation }}</div>
    </div>
</template>
