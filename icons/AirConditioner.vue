
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,3.41v7.64A1.9,1.9,0,0,1,20.59,13H17.73V10.09H6.27V13H3.41a1.9,1.9,0,0,1-1.91-1.9V3.41A1.9,1.9,0,0,1,3.41,1.5H20.59A1.9,1.9,0,0,1,22.5,3.41Z"/><line class="cls-1" x1="8.18" y1="12.95" x2="6.27" y2="12.95"/><line class="cls-1" x1="17.73" y1="12.95" x2="15.82" y2="12.95"/><path class="cls-1" d="M10.09,13v4.78a1.91,1.91,0,0,1-1.91,1.91h0a1.92,1.92,0,0,1-1.91-1.91h0"/><path class="cls-1" d="M13.91,13v7.64a1.9,1.9,0,0,0,1.91,1.91h0a1.91,1.91,0,0,0,1.91-1.91h0"/><line class="cls-1" x1="17.73" y1="5.32" x2="19.64" y2="5.32"/><line class="cls-1" x1="4.36" y1="5.32" x2="15.82" y2="5.32"/></svg>
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