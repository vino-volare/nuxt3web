<template>
    <header>
        <h1>Vino Tokino</h1>
    </header>
    <div>
        <slot />
    </div>
    <footer>
        <p>footer</p>
    </footer>
</template>
<style lang="scss">
    header{
        background-color: gray;
        width: 100vw;
    }
    h1{
        size: 3rem;
    }
</style>