<template>
  <scroll-view>
    <view class="container">
      <header />
      <image
        :style="{width: 420, height: 350}"
        :source="{uri: 'https://wallpapersmug.com/large/c9bf30/dark-minimal-marvels-avengers-game-logo.jpg'}"
      />
      <view class="card">
        <view class="card_content" v-for="member in members" :key="member.id">
            <touchable-opacity :on-press="() => this.props.navigation.navigate(member.route)">
                <text>{{ member.name }}</text>
            </touchable-opacity>
        </view>
    </view>
    <footer />
    </view>
  </scroll-view>
</template>

<script> 
  import header from "./basic/header";
  import footer from "./basic/footer";
  export default {
    components: {
      header,
      footer
    },
    data: function() {
      return {
        members: [
            {
                "name": "Tony Stark/Iron Man",
                "route": "ironman",
                "id": 1
            },
            {
                "name": "Steve Rogers/Captain America",
                "route": "steve",
                "id": 2
            },
            {
                "name": "Thor Odinson",
                "route": "thor",
                "id": 3
            },
            {
                "name": "Bruce Banner/HULK",
                "route": "hulk",
                "id": 4
            },
            {
                "name": "Natasha Romanoff/Black Widow",
                "route": "natasha",
                "id": 5
            },
            {
                "name": "Clint Barton/Hawkeye",
                "route": "clint",
                "id": 6
            },
            {
                "name": "T'Challa/Black Panther",
                "route": "panther",
                "id": 7
            },
            {
                "name": "Stephen Strange/Doctor Strange",
                "route": "strange",
                "id": 8
            },
            {
                "name": "Vision",
                "route": "vision",
                "id": 9
            },
            {
                "name": "Wanda Maximoff/Scarlet Witch",
                "route": "witch",
                "id": 10
            },
            {
                "name": "Scott Lang/Ant Man",
                "route": "antman",
                "id": 11
            },
            {
              "name": "Carol Danvers/Captain Marvel",
              "route": "marvel",
              "id": 12
            },
            {
              "name": "Peter Parker/Spiderman",
              "route": "spider",
              "id": 13
            }
        ]
      }
    }
  }
</script>
 
<style>
.container {
  display: flex;
  flex-direction: column;
  background-color: white;
}
.text-color-primary {
  color: blue;
}
.card {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin: 10px 0px;
}
.card_content {
    background-color: #ddd;
    padding: 15px;
    margin: 10px;
}
</style>
