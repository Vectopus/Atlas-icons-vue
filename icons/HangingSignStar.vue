
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="1.46" x2="23.5" y2="1.46"/><rect class="cls-1" x="2.42" y="1.46" width="19.17" height="3.83"/><polygon class="cls-1" points="19.67 5.29 4.33 5.29 4.33 18.71 12 22.54 19.67 18.71 19.67 5.29"/><polygon class="cls-1" points="12 12.96 12.6 14.22 13.96 14.42 12.98 15.4 13.21 16.79 12 16.14 10.79 16.79 11.02 15.4 10.04 14.42 11.4 14.22 12 12.96"/><path class="cls-1" d="M8.17,10.08A8.74,8.74,0,0,1,12,9.13a8.74,8.74,0,0,1,3.83.95"/></svg>
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