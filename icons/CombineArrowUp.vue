
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,23.5V21A5.73,5.73,0,0,0,15.9,16.1l-4-2.39A5.71,5.71,0,0,1,9.14,8.8V6.32"/><line class="cls-1" x1="9.14" y1="2.5" x2="9.14" y2="23.5"/><polyline class="cls-1" points="5.32 6.32 9.14 2.5 12.96 6.32"/><line class="cls-1" x1="9.14" y1="12.05" x2="9.14" y2="4.41"/></svg>
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