<template lang="">
    <h2>{{title}}</h2>
    <ul>
        <li v-for="url in urls"> {{url}}</li>
    </ul>
</template>
<script>
export default {
    props: {
        title: {
            String,
            required: false
        },
        urls: {
            Array,
            required: true
        }
    }
}
</script>
<style lang="scss" scoped>
ul {
    margin-top: 5px;
    margin-bottom: 15px;
    display: flex;
    flex-direction: column;

    li {
        padding: 7px 0;
        color: grey;
    }
}
</style>