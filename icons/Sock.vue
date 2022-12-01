
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="13.36" height="5.73"/><path class="cls-1" d="M17.25,22.5H8.18a5.74,5.74,0,0,1-5.73-5.73V7.23H13.91v2.86A2,2,0,0,0,16,12h1a5.39,5.39,0,0,1,5.45,4.73A5.24,5.24,0,0,1,17.25,22.5Z"/><path class="cls-1" d="M10.09,20.59V22.5H8.18a5.74,5.74,0,0,1-5.73-5.73V14.86H4.36A5.74,5.74,0,0,1,10.09,20.59Z"/></svg>
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