<template>
    <div class="h-100vh w-100vw flex flex-nowrap overflow-hidden">
        <leftMenu class="shrink-0" />
        <div class="flex-1 p-4 overf">
            <slot />
        </div>
    </div>
</template>
<script lang="ts" setup>
import leftMenu from '../components/menu/LeftMenu.vue';
</script>