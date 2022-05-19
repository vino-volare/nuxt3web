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
        height: 300px;
        background-image: url('/assets/img/ばってん星川 完成品 色収差ver.png');
        background-size: cover;
        position: relative;
    }
    header::before{
        content: "\A\A\ATokino Vino";
        white-space: pre;
        position: absolute;
        top: 0;
        height: 284px;
        width: 100vw;
        padding-top: 16px;
        text-align: center;
        font-family: 'F1Black';
        font-size: 40px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        backdrop-filter: blur(8px);
    }
</style>