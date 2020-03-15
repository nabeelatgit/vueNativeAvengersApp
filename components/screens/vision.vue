<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://wallpapersmug.com/large/cd7e65/vision-in-avengers-infinity-war-8k-poster.jpg'}"
            />
            <text class="member_title">Vision</text>
            <text class="member_details">
                Vision is a fictional superhero appearing in American comic books published by Marvel Comics. He is an android and a member of the Avengers who first appeared in The Avengers #57 (October 1968). He is loosely based on the Timely Comics character of the same name.
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