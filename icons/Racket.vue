
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="20.59" x2="3.41" y2="22.5"/><path class="cls-1" d="M20.5,12.2c-2.55,2.56-7.89,4-10.3,1.6s-1-7.75,1.6-10.3a6.34,6.34,0,0,1,9-.27A6.34,6.34,0,0,1,20.5,12.2Z"/><polyline class="cls-1" points="10.2 13.8 9.58 14.42 2.46 21.55"/><polyline class="cls-1" points="11.75 14.73 14.56 11.93 17.04 9.44 19.53 6.96 21.82 4.66"/><polyline class="cls-1" points="9.27 12.25 12.07 9.44 14.56 6.96 17.04 4.47 19.34 2.17"/><polyline class="cls-1" points="11.47 3.87 14.56 6.96 17.04 9.44 20.13 12.53"/><polyline class="cls-1" points="17 14.37 14.56 11.93 12.07 9.44 9.63 7"/><polyline class="cls-1" points="14.43 1.85 17.04 4.47 19.53 6.96 22.15 9.57"/></svg>
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