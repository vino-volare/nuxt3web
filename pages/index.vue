<template>
    <NuxtLayout name="home">
        <p>アマチュアイラストレーター</p>
        <nav>
            <h2>SOCIAL</h2>
            <ul class="list">
                <li class="socialLink">
                    <NuxtLink src="https://twitter.com/VinoVolare" target="_blank">
                        <img src="/assets/img/Twitter social icons - square - blue.svg">
                    </NuxtLink>
                </li>
                <li class="socialLink">
                    <NuxtLink src="https://www.pixiv.net/users/24802125" target="_blank">
                        <img src="/assets/img/logo_icon.png">
                    </NuxtLink>
                </li>
                <li class="socialLink">
                    <NuxtLink src="https://www.youtube.com/channel/UCP-bXu2xtY2GqDdAKk_ys4w" target="_blank">
                        <img src="/assets/img/youtube_social_square_red.png">
                    </NuxtLink>
                </li>
                <li class="socialLink">
                    <NuxtLink src="https://www.twitch.tv/tokino_ch" target="_blank">
                        <img src="/assets/img/TwitchGlitchPurple.svg">
                    </NuxtLink>
                </li>
            </ul>
        </nav>
    </NuxtLayout>
</template>

<script setup lang="ts">
</script>

<style scoped>
img{
    max-width: 100%;
}
.list{
    display: flex;
    padding-left: 8px;
    padding-right: 8px;
    padding-top: 8px;
}
.socialLink{
    width: 100%;
}
h2{
    font-family: 'F1Bold';
    width: 100vw;
    text-align: center;
}
p{
    width: 100vw;
    text-align: center;
    padding: 8px;
}
@media screen and (min-width:600px) {
    .list{
        padding-left: calc((100vw - 600px) / 2);
        padding-right: calc((100vw - 600px) / 2);
    }
}
</style>