<script setup lang="ts">

const toggleBackground = () => {
    const backgroundMode = document.getElementById("backgroundMode") as HTMLInputElement | null;
    const header = document.getElementById("header") as HTMLHeadElement | null;
    const footer = document.getElementById("footer") as HTMLElement | null;

    if (backgroundMode?.checked) {
        document.body?.classList.replace("bg-neutral-950", "bg-neutral-200");
        document.body?.classList.replace("text-white", "text-black");

        header?.classList.replace("bg-neutral-900", "bg-neutral-300");

        footer?.classList.replace("bg-neutral-900", "bg-neutral-300");
    }
    else {
        document.body?.classList.replace("bg-neutral-200", "bg-neutral-950");
        document.body?.classList.replace("text-black", "text-white");

        header?.classList.replace("bg-neutral-300", "bg-neutral-900");

        footer?.classList.replace("bg-neutral-300", "bg-neutral-900");

    }

}
</script>

<template>
    <label class="inline-flex items-center cursor-pointer">
        <input id="backgroundMode" type="checkbox" value="" class="sr-only peer" @click="toggleBackground">
        <div
            class="relative w-11 h-6 bg-gray-200 peer-focus:outline-none rounded-full peer dark:bg-neutral-700 peer-checked:after:translate-x-full rtl:peer-checked:after:-translate-x-full peer-checked:after:border-white after:content-[''] after:absolute after:top-[2px] after:start-[2px] after:bg-white after:border-gray-300 after:border after:rounded-full after:h-5 after:w-5 after:transition-all dark:border-gray-600 peer-checked:bg-violet-600">
        </div>
    </label>
</template>