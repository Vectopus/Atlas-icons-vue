
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="14.86 12.04 22.5 12.04 22.5 8.23 18.68 8.23 5.32 8.23 1.5 8.23 1.5 12.04 9.14 12.04"/><line class="cls-1" x1="3.41" y1="12.05" x2="3.41" y2="21.59"/><line class="cls-1" x1="20.59" y1="12.05" x2="20.59" y2="21.59"/><polygon class="cls-1" points="12 14.91 5.32 8.23 18.68 8.23 12 14.91"/><path class="cls-1" d="M1.5,4.41H9.14a0,0,0,0,1,0,0v.51A3.31,3.31,0,0,1,5.83,8.23h-1A3.31,3.31,0,0,1,1.5,4.92V4.41A0,0,0,0,1,1.5,4.41Z"/><path class="cls-1" d="M14.86,4.41H22.5a0,0,0,0,1,0,0v.51a3.31,3.31,0,0,1-3.31,3.31h-1a3.31,3.31,0,0,1-3.31-3.31V4.41A0,0,0,0,1,14.86,4.41Z"/></svg>
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