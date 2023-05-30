<script setup>
import MainNavLayout from '@/Layouts/MainNavLayout.vue';
import MainSidebarLayout from '@/Layouts/MainSidebarLayout.vue';
</script>

<template>
    <MainNavLayout />
    <MainSidebarLayout />

    <slot />

</template>
