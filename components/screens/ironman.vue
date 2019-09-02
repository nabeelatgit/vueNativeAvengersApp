<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://nerdist.com/wp-content/uploads/2019/03/IM-header-1200x676.jpg'}"
            />
            <text class="member_title">Tony Stark aka Iron Man</text>
            <text class="member_details">
                Iron Man is a fictional superhero appearing in American comic books published by Marvel Comics. The character was co-created by writer and editor Stan Lee, developed by scripter Larry Lieber, and designed by artists Don Heck and Jack Kirby. The character made his first appearance in Tales of Suspense #39 (cover dated March 1963), and received his own title in Iron Man #1 (May 1968).
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