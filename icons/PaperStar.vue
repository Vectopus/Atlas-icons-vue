
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 6.27 12.6 7.53 13.95 7.73 12.97 8.71 13.2 10.09 12 9.44 10.8 10.09 11.03 8.71 10.05 7.73 11.4 7.53 12 6.27"/><path class="cls-1" d="M20.59,1.5h0A1.91,1.91,0,0,1,22.5,3.41V5.32a0,0,0,0,1,0,0H18.68a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,20.59,1.5Z"/><path class="cls-1" d="M14.86,18.68H1.5v1.91A1.9,1.9,0,0,0,3.41,22.5H16.77a1.91,1.91,0,0,1-1.91-1.91Z"/><path class="cls-1" d="M5.32,18.68V3.41A1.9,1.9,0,0,1,7.23,1.5H20.59a1.91,1.91,0,0,0-1.91,1.91V20.59a1.9,1.9,0,0,1-1.91,1.91h0"/><line class="cls-1" x1="8.18" y1="14.86" x2="15.82" y2="14.86"/></svg>
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