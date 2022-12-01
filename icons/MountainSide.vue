
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.61 22.5 1.48 22.5 1.48 12.96 19.61 22.5"/><path class="cls-1" d="M1.48,13,6.78,2.34A1.52,1.52,0,0,1,8.15,1.5a1.5,1.5,0,0,1,1.37.87L15,13.18"/><polyline class="cls-1" points="5.29 5.32 7.21 8.18 8.16 7.23 10.07 8.18 11.43 6.37"/><polygon class="cls-1" points="21.52 15.82 13.89 15.82 17.7 6.27 21.52 15.82"/><line class="cls-1" x1="17.7" y1="15.82" x2="17.7" y2="21.55"/></svg>
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