
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><ellipse class="cls-1" cx="12" cy="12" rx="12.91" ry="8.21" transform="translate(-4.97 12) rotate(-45)"/><path class="cls-1" d="M19.35,7.52a25.72,25.72,0,0,1-4.86,7,25.72,25.72,0,0,1-7,4.86"/><path class="cls-1" d="M4.65,16.48a25.72,25.72,0,0,1,4.86-7,25.72,25.72,0,0,1,7-4.86"/><path class="cls-1" d="M14.85,1.67a10.88,10.88,0,0,0,1.63,3,11.82,11.82,0,0,0,1.33,1.54,11.82,11.82,0,0,0,1.54,1.33,10.88,10.88,0,0,0,3,1.63"/><path class="cls-1" d="M9.15,22.33a10.88,10.88,0,0,0-1.63-3,11.82,11.82,0,0,0-1.33-1.54,11.82,11.82,0,0,0-1.54-1.33,10.88,10.88,0,0,0-3-1.63"/></svg>
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