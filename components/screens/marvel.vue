<template functional>
    <scroll-view>
        <view class="member">
            <image
                :style="{width: 420, height: 350}"
                :source="{uri: 'https://wallpapersmug.com/large/e38186/poster-captain-marvel-movie-2019.jpg'}"
            />
            <text class="member_title">Carol Danvers aka Captain Marvel</text>
            <text class="member_details">
                Carol Susan Jane Danvers is a fictional superhero appearing in American comic books published by Marvel Comics. Created by writer Roy Thomas and artist Gene Colan, Danvers first appeared as an officer in the United States Air Force and a colleague of the Kree superhero Mar-Vell in Marvel Super-Heroes #13 (March 1968). Danvers later became the first incarnation of Ms. Marvel in Ms. Marvel #1 (cover-dated Jan. 1977) after her DNA was fused with Mar-Vell's during an explosion, giving her superhuman powers. Debuting in the Silver Age of comics, the character was featured in a self-titled series in the late 1970s before becoming associated with the superhero teams the Avengers and the X-Men. The character has also been known as Binary, Warbird and Captain Marvel at various points in her history. Danvers has been labeled as Marvel's most notable female hero, and frequently touted as one of the most powerful characters in the franchise.
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