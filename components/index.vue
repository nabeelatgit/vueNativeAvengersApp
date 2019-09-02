<template>
  <scroll-view>
    <view class="container">
      <header />
      <image
        :style="{width: 420, height: 350}"
        :source="{uri: 'https://filmschoolrejects.com/wp-content/uploads/2019/04/endgame-poster-art-700x500.jpg'}"
      />
      <view class="card">
        <view class="card_content" v-for="member in members" :key="member.id">
            <touchable-opacity :on-press="() => this.props.navigation.navigate(member.route)">
                <text>{{ member.name }}</text>
            </touchable-opacity>
        </view>
    </view>
    </view>
  </scroll-view>
</template>

<script> 
  import header from "./basic/header";
  export default {
    components: {
      header
    },
    data: function() {
      return {
        members: [
            {
                "name": "Thanos",
                "route": "thanos",
                "id": 1
            },
            {
                "name": "Tony Stark/Iron Man",
                "route": "ironman",
                "id": 2
            },
            {
                "name": "Steve Rogers/Captain America",
                "id": 3
            },
            {
                "name": "Thor Odinson",
                "id": 4
            },
            {
                "name": "Bruce Banner/HULK",
                "id": 5
            },
            {
                "name": "Natasha Romanoff/Black Widow",
                "id": 6
            },
            {
                "name": "Clint Barton/Hawkeye",
                "id": 7
            },
            {
                "name": "T'Challa/Black Panther",
                "id": 8
            },
            {
                "name": "Stephen Strange/Doctor Strange",
                "id": 9
            },
            {
                "name": "Vision",
                "id": 10
            },
            {
                "name": "Wanda Maximoff/Scarlet Witch",
                "id": 11
            },
            {
                "name": "Scott Lang/Ant Man",
                "id": 12
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
