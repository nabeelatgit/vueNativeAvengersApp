<template>
    <view class="container">
        <view v-for="user in users" :key="user.id" class="list">
            <text class="list_content">{{ user.name }}</text>
        </view>
        <view class="addUser">
            <touchable-opacity :on-press="newUser">
                <text class="abb_btn">ADD</text>
            </touchable-opacity>
        </view>
    </view>
</template>

<script>
    export default {
        data: function() {
            return {
                users: [
                    {
                        "id": 0,
                        "name": "Nabeel"
                    },
                    {
                        "id": 1,
                        "name": "Shibu"
                    }
                ]
            }
        },
        methods: {
            newUser() {
                this.users.push({
                    "id": this.users.length + 1,
                    "name": "Srini"
                });
            }
        }
    }
</script>

<style>
.list_content {
    font-size: 25px;
    color: red;
}
</style>