<template>
  <Html lang="ja">
    <Head>
      <Title>{{ title }}</Title>
      <Meta name="description" :content="title" />
      <Link rel="apple-touch-icon" type="image/png" href="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto/v1653465095/website/static/apple-touch-icon-180x180_z7uaza.png" />
      <Link rel="icon" type="image/png" href="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto/v1653465182/website/static/icon-192x192_oudco0.png" />
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
  color: white;
}
</style>
