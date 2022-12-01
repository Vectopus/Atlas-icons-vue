
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="7.23" cy="16.86" r="1.91"/><circle class="cls-1" cx="16.77" cy="16.86" r="1.91"/><line class="cls-1" x1="14.86" y1="16.86" x2="9.14" y2="16.86"/><path class="cls-1" d="M5.32,16.86H2.45L1.5,14V11.14L1.76,11A16.86,16.86,0,0,1,9.3,9.23h0a20.16,20.16,0,0,1,10.34,2.86h0L22.5,14v2.86H18.68"/><polyline class="cls-1" points="5.59 9.64 11.04 13.04 19.64 12.09"/></svg>
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