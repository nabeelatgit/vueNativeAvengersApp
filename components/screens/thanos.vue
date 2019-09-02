<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://wallpapersmug.com/large/5a3fd5/thanos-avengers-infinity-4k.jpg'}"
            />
            <text class="member_title">Thanos</text>
            <text class="member_details">
                Thanos is a fictional supervillain appearing in American comic books published by Marvel Comics. The character, created by writer/artist Jim Starlin, first appeared in The Invincible Iron Man #55 (cover dated February 1973). Thanos is one of the most powerful villains in the Marvel Universe and has clashed with many heroes including the Avengers, the Guardians of the Galaxy, the Fantastic Four, and the X-Men.
            </text>
        </view>
    </scroll-view>
</template>

<style>
.member_title {
    font-size:30;
    padding:15px;
}
.member_details {
    padding: 15px;
}
</style>