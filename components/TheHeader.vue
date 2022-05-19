<template>
    <header>
        <nav>
            <div>
                <NuxtLink to="/about" class="menu">about</NuxtLink>
                <NuxtLink to="/contact" class="menu">contact</NuxtLink>
            </div>
            <NuxtLink to="/">
                <img src="/img/vino_volare_noword_final.svg" />
            </NuxtLink>
        </nav>
    </header>
</template>

<script setup lang="ts">

</script>

<style scoped>
    nav{
        position: absolute;
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        align-items: center;
        height: 100px;
        width: 100vw;
    }
    img{
        padding-left: 8px;
        max-width: 50%;
    }
    .menu{
        color: inherit;
        text-decoration: none;
        margin: 1rem;
        font-family: 'F1Regular';
    }
    h1{
        size: 3rem;
    }
</style>