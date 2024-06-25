<script setup lang="ts">
    import type { ButtonHTMLAttributes } from "vue";

    interface MyButtonProps extends ButtonHTMLAttributes {}

    defineProps<MyButtonProps>();
</script>

<template>
    <button><slot /></button>
</template>
