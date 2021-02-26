<template>
    <div>
        <h1>{{msg}}</h1>
    </div>
</template>

<script>
export default {
    data () {
        return {
            msg: 'Hello'
        }
    },
    methods: {

    },
    mounted () {

    }
}
</script>

<style lang="less" scoped>
@import '../mixins/style.less';

h1 {
    padding-top: 30vh;
    font-size: 20vh;
    text-align: center;
}
</style>
