<template>
    <view>
        <text>{{title}}</text>
        <button title="Go to Home" :on-press="() => navigate('homeScreen')"/>
    </view>
</template>

<script>
    export default {
        props: {
            navigate: {
                type: Function,
                required: true
            }
        },
        data () {
            return {
                title: "I am SCREEN 1!"
            }
        }
    }
</script>

<style>
</style>
