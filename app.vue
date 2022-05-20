<template>
  <Html lang="ja">
    <Head>
      <Title>{{ title }}</Title>
      <Meta name="description" :content="title" />
    </Head>
    <NuxtPage />
  </Html>
</template>
<script setup>
const title = ref('Tokino Vino')
</script>
<style>
*{
  margin: 0;
  box-sizing: border-box;
  list-style: none;
  padding: 0;
}
html{
  font: 400 16px -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
}
</style>
