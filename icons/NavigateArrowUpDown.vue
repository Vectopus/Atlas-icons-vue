
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="9 6 5 2 1 6"/><polyline class="cls-1" points="15 18 19 22 23 18"/><path class="cls-1" d="M5,2V18.5A3.5,3.5,0,0,0,8.5,22h0A3.5,3.5,0,0,0,12,18.5V5.5A3.5,3.5,0,0,1,15.5,2h0A3.5,3.5,0,0,1,19,5.5V22"/></svg>
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