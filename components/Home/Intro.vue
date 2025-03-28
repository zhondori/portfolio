<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.png" alt="Alisher Zhondori"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
      Hello!
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Alisher aka Zhondori, I work as a frontend engineer from
      Tashkent, Uzbekistan. I specialize in building web applications and sites
      using Javascript, React, Vue &amp; Node.
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Frontend Engineer at
      <a href="https://magicbot.uz" target="_blank" class="underline">Magicbot</a>, and
      by night (and weekends), I'm busy tinkering with some random tool or app
      that I am building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Alisher Usmonov (Zhondori)",
  description:
    "I'm Alisher aka Zhondori, I work as a frontend engineer from Tashkent, Uzbekistan. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
