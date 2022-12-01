
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="achievment"><path class="cls-1" d="M18.67,8.17a6.63,6.63,0,0,1-2.86,5.46,6.65,6.65,0,0,1-7.62,0A6.66,6.66,0,1,1,18.67,8.17Z"/><polygon class="cls-2" points="12 4.43 13.18 6.89 15.81 7.29 13.9 9.2 14.35 11.9 12 10.63 9.65 11.9 10.1 9.2 8.19 7.29 10.82 6.89 12 4.43"/><path class="cls-1" d="M15.81,13.63V21.5L12,18.64,8.19,21.5V13.63a6.65,6.65,0,0,0,7.62,0Z"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>