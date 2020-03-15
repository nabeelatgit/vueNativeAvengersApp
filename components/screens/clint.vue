<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://wallpapersmug.com/large/878b59/hawkeye-avengers-infinity-war-2018-4k-artwork.jpg'}"
            />
            <text class="member_title">Clint Barton aka Hawkeye</text>
            <text class="member_details">
                Hawkeye (Clinton Francis Barton) is a fictional superhero appearing in American comic books published by Marvel Comics. Created by writer Stan Lee and artist Don Heck, the character first appeared as a villain in Tales of Suspense #57 (Sept. 1964) and later joined the Avengers in The Avengers #16 (May 1965). He has been a prominent member of the team ever since. He was also ranked at #44 on IGN's Top 100 Comic Book Heroes list.
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