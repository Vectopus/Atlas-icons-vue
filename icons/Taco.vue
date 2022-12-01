
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M3.41,8.19H20.59A1.91,1.91,0,0,1,22.5,10.1v0A10.5,10.5,0,0,1,12,20.6h0A10.5,10.5,0,0,1,1.5,10.1v0A1.91,1.91,0,0,1,3.41,8.19Z" transform="translate(24 28.79) rotate(180)"/><path class="cls-1" d="M2.46,14.22c.24-.89-.55-4.13-.1-4.92s2-.76,2.66-1.41.62-2.2,1.41-2.66,2.12.35,3,.11,1.62-1.6,2.56-1.6,1.69,1.36,2.56,1.6,2.22-.56,3-.11.76,2,1.41,2.66,2.2.62,2.66,1.42-.34,4-.1,4.91"/><line class="cls-1" x1="5.32" y1="15.83" x2="7.23" y2="17.74"/><line class="cls-1" x1="12.95" y1="14.87" x2="12.95" y2="16.78"/><line class="cls-1" x1="17.73" y1="14.87" x2="17.73" y2="17.74"/><line class="cls-1" x1="9.14" y1="11.05" x2="11.05" y2="12.96"/></svg>
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