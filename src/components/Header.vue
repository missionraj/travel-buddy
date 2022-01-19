
<template>
    <div class="bg-blue-500 flex items-center text-white p-2">
        <h1 class="flex-1">Travel Buddy</h1>
        <div class="flex items-center">
            Explore New Places
            <div class="flex items-center bg-blue-400 p-1 rounded">
                <div>
                    <MagnifyIcon />
                </div>
                <input type="text" class="bg-blue-400 outline-none text-black px-2" />
            </div>
        </div>
    </div>
</template>
<script setup lang="ts">

import MagnifyIcon from 'vue-material-design-icons/Magnify.vue';
</script>

<style scoped>
</style>
