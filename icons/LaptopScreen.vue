
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.32,3.41H18.68a1.91,1.91,0,0,1,1.91,1.91V16.77a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V5.32A1.91,1.91,0,0,1,5.32,3.41Z"/><path class="cls-1" d="M1.5,16.77h21a0,0,0,0,1,0,0v1.91a1.91,1.91,0,0,1-1.91,1.91H3.41A1.91,1.91,0,0,1,1.5,18.68V16.77a0,0,0,0,1,0,0Z"/></svg>
</template>
<script>
    export default {
        props: {
            size: {
                type: Number,
                default: 24,
                required: false,
            },
            weight: {
                type: Number,
                default: 2,
                required: false,
            },
        }
    }
</script>
<style scoped>
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>