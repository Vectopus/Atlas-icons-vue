
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.35,15.15a7.35,7.35,0,0,1-14.7,0C4.65,8.85,12,1.5,12,1.5S19.35,8.85,19.35,15.15Z"/><path class="cls-1" d="M9.88,16.62a3,3,0,0,1,0-4.24"/><polygon class="cls-2" points="15 10.5 12 13.5 12 10.5 15 10.5"/><polygon class="cls-2" points="9 18.5 12 15.5 12 18.5 9 18.5"/><path class="cls-1" d="M13.41,11.67l.71.71a3,3,0,0,1,0,4.24"/><line class="cls-1" x1="9.88" y1="16.62" x2="10.59" y2="17.33"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>