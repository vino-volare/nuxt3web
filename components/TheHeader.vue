<template>
    <header>
        <nav>
            <div>
                <NuxtLink to="/about" class="menu">about</NuxtLink>
                <NuxtLink to="/contact" class="menu">contact</NuxtLink>
            </div>
            <NuxtLink to="/">
                <h1>Vino Tokino</h1>
            </NuxtLink>
        </nav>
    </header>
</template>

<script setup lang="ts">

</script>

<style scoped>
    nav{
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        align-items: center;
        height: 100px;
    }
    .menu{
        color: inherit;
        text-decoration: none;
        margin: 1rem;
    }
    header{
        background-color: gray;
        height: 300px;
    }
    h1{
        size: 3rem;
    }
</style>