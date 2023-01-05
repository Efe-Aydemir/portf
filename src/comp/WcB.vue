<template>
    <button :title="props.btitle"
    class="
    text-lg
    py-1
    px-10
    rounded-md
    bg-white
    text-black
    transition-all
    duration-300
    hover:shadow-xl
    hover:shadow-black
    hover:px-12
    hover:rounded-lg
    hover:font-bold
    "
    ><slot></slot></button>
</template>



<script setup>
import { defineProps } from 'vue';
const props = defineProps(['btitle'])
</script>