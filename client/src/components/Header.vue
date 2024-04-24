<script setup lang="ts">
import { RouterLink } from 'vue-router';
import ToggleBackground from './ToggleBackground.vue';
</script>

<template>
    <header id="header"
        class="h-16 w-full border-b-2 border-b-violet-800 top-0 bg-neutral-900 sticky flex items-center px-6 shadow-xl shadow-violet-700 mb-14 z-10">
        <nav class="flex-grow">
            <ul class="flex items-center gap-6">
                <li class="cursor-pointer opacity-75">
                    <RouterLink to="/sign-up">sign up</RouterLink>
                </li>
                <li class="cursor-pointer opacity-75">
                    sign in
                </li>
                <li class="cursor-pointer text-lg">
                    |
                </li>
                <li class="cursor-pointer text-lg">
                    <RouterLink to="/">home</RouterLink>
                </li>
            </ul>
        </nav>
        <div class="flex-grow"></div>
        <ToggleBackground />
    </header>
</template>