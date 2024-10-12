<script setup>
import { siteMetaData } from './data'

useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: () => siteMetaData,
})
</script>

<template>
  <div class="bg-[#F1F2F4] dark:text-zinc-300   dark:bg-slate-950">
    <NuxtLoadingIndicator />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style>

html.dark{
  color-scheme: dark;
}
</style>
