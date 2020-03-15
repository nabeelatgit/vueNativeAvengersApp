<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://wallpapersmug.com/large/e0bc06/ant-man-in-avengers-infinity-war-2018-4k-artwork.jpg'}"
            />
            <text class="member_title">Scott Lang aka Ant Man</text>
            <text class="member_details">
                Ant-Man is the name of several superheroes appearing in books published by Marvel Comics. Created by Stan Lee, Larry Lieber and Jack Kirby, Ant-Man's first appearance was in Tales to Astonish #35 (September 1962). The persona was originally the brilliant scientist Hank Pym's superhero alias after inventing a substance that can change size, but reformed thieves Scott Lang and Eric O'Grady also took on the mantle after the original changed his superhero identity to various other aliases, such as Giant-Man, Goliath, and Yellowjacket.
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