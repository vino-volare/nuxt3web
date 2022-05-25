<template>
    <div>
        <header>
            <TheHeader />
        </header>
        <main><slot /></main>
        <TheFooter />
    </div>
</template>
<script setup>
useHead({
    meta: [{name: 'robots', content: 'noindex,nofollow'}],
})
</script>
<style scoped>
    div{
        display: flex;
        flex-direction: column;
        min-height: 100vh;
    }
    main{
        flex: 1;
    }
    header{
        height: 100px;
        background-color: rgb(0, 0, 0);
    }
</style>