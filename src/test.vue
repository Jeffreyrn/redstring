<style>
body{
    background-color: #ccc;
}
</style>
<template>
    <p v-on:click="test">test.vue loaded</p>
</template>
<script>

module.exports = {
    methods: {
        test: function () {
            console.log('run it.');
        }
    }
} 

</script>