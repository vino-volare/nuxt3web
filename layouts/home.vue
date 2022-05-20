<template>
    <div>
        <header>
            <img src="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto/v1653030180/website/static/%E3%81%B0%E3%81%A3%E3%81%A6%E3%82%93%E6%98%9F%E5%B7%9D_%E5%AE%8C%E6%88%90%E5%93%81_%E8%89%B2%E5%8F%8E%E5%B7%AEver_wgxmcn.png"
            srcset="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_600/v1653030180/website/static/%E3%81%B0%E3%81%A3%E3%81%A6%E3%82%93%E6%98%9F%E5%B7%9D_%E5%AE%8C%E6%88%90%E5%93%81_%E8%89%B2%E5%8F%8E%E5%B7%AEver_wgxmcn.png 600w"
            sizes="100vw">
            <TheHeader />
        </header>
        <main><slot /></main>
        <TheFooter />
    </div>
</template>
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
        width: 100%;
        height: 300px;
        position: relative;
        overflow: hidden;
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
    header img{
        width: 100%;
        height: auto;
        max-width: inherit;
        position: absolute;
        top: -30%;
        left: 0;
        z-index: -1;
    }
</style>