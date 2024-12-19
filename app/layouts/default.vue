<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center mt-5">
      <div>
        <NuxtLink class="text-xl front-semibold p-2 hover:bg-gray-200" to="/">
          Piotr Jura
        </NuxtLink>
      </div>
      <Menu />
    </header>
    <main class="p-2">
      <slot />
    </main>
  </div>
</template>
<script setup>
useHead({
  titleTemplate: "%s - Piotr Jura",
});
</script>
