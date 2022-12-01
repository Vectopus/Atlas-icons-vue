
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.09,3.41,9.14,1.5H6.27V7.23H17.73A3.24,3.24,0,0,0,14.89,4Z"/><line class="cls-1" x1="4.36" y1="7.23" x2="19.64" y2="7.23"/><polygon class="cls-1" points="6.27 7.23 17.73 7.23 15.82 22.5 8.18 22.5 6.27 7.23"/><polyline class="cls-1" points="12.32 11.04 11.04 14.86 12.96 14.86 11.68 18.68"/></svg>
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