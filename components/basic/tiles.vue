<template>
    <view class="card">
        <view class="card_content" v-for="member in members" :key="member.id">
            <touchable-opacity>
                <text>{{ member.name }}</text>
            </touchable-opacity>
        </view>
    </view>
</template>

<script>
    export default {
        props: {
            navigation: {
                type: Object
            }
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
    };
</script>

<style>
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