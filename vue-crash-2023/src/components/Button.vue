<template>
    <button @click="onClick()" :style="{background: color}" class="btn">{{text}}</button>
</template>

<script>
    export default {
        name: 'App-Button',
        props: {
            text: String,
            color: String
        },
        methods: {
            onClick() {
                console.log('click')
            }
        }
    }
</script>