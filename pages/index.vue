<template>
    <NuxtLayout name="home">
        <p>アマチュアイラストレーター</p>
        <nav>
            <h2>SOCIAL</h2>
            <div class="list">
                <NuxtLink class="link" to="https://twitter.com/VinoVolare" target="_blank">
                    <img src="/assets/img/Twitter social icons - square - blue.svg" loading="lazy">
                </NuxtLink>
                <NuxtLink class="link" to="https://www.pixiv.net/users/24802125" target="_blank">
                    <img src="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_150/v1653036064/website/static/logo_icon_euqxh2.png"
                    srcset="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_100/v1653036064/website/static/logo_icon_euqxh2.png 100w,
                    https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_150/v1653036064/website/static/logo_icon_euqxh2.png 150w"
                    sizes="(min-width:600px) 25vw, 150px" loading="lazy">
                </NuxtLink>
                <NuxtLink class="link" to="https://www.youtube.com/channel/UCP-bXu2xtY2GqDdAKk_ys4w" target="_blank">
                    <img src="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_150/v1653036094/website/static/youtube_social_square_red_fn8a06.png"
                    srcset="https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_100/v1653036094/website/static/youtube_social_square_red_fn8a06.png 100w,
                    https://res.cloudinary.com/tokino/image/upload/f_auto,q_auto,w_150/v1653036094/website/static/youtube_social_square_red_fn8a06.png 150w"
                    sizes="(min-width:600px) 25vw, 150px" loading="lazy">
                </NuxtLink>
                <NuxtLink class="link" to="https://www.twitch.tv/tokino_ch" target="_blank">
                    <img src="/assets/img/TwitchGlitchPurple.svg" loading="lazy">
                </NuxtLink>
            </div>
        </nav>
    </NuxtLayout>
</template>

<script setup lang="ts">
</script>

<style scoped>
img{
    max-width: 100%;
}
nav{
    padding-top: 16px;
}
.link{
    display: block;
    width: 100%;
    height: fit-content;
}
.list{
    display: flex;
    padding-left: 8px;
    padding-right: 8px;
    padding-top: 8px;
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