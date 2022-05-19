<template>
    <TheHeader />
    <main><slot /></main>
    <TheFooter />
</template>
<style scoped>
    main{
        flex: 1;
    }
    header{
        height: 100px;
        background-color: aqua;
    }
</style>