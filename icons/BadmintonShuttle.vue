
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="3.9 14.3 9.7 1.25 13.33 1.98 15.5 4.15 18.4 5.6 19.85 8.5 22.02 10.67 22.75 14.3 9.7 20.09"/><line class="cls-1" x1="15.5" y1="4.15" x2="6.08" y2="16.47"/><line class="cls-1" x1="19.85" y1="8.5" x2="7.53" y2="17.92"/><path class="cls-1" d="M9.7,20.09,8.25,21.55a4.1,4.1,0,0,1-5.8-5.8L3.91,14.3l2.17,2.18.72.72.72.72Z"/></svg>
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