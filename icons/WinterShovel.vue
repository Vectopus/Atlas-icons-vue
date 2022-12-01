
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12.02" y1="5.32" x2="12.02" y2="14.86"/><path class="cls-1" d="M10.11,22.5a8.07,8.07,0,0,0,0-7.64"/><path class="cls-1" d="M13.93,22.5a8.13,8.13,0,0,0,0-7.64"/><path class="cls-1" d="M17.75,14.86a8.13,8.13,0,0,1,0,7.64H6.3a8.13,8.13,0,0,0,0-7.64Z"/><polygon class="cls-1" points="14.89 4.36 12.02 5.32 9.16 4.36 9.16 1.5 14.89 1.5 14.89 4.36"/></svg>
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