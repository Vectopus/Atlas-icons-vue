
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.35,15.15a7.35,7.35,0,0,1-14.7,0C4.65,8.85,12,1.5,12,1.5S19.35,8.85,19.35,15.15Z"/><path class="cls-1" d="M8.5,9.09h2.57a4.43,4.43,0,0,1,4.43,4.43v2.57a0,0,0,0,1,0,0H12.93A4.43,4.43,0,0,1,8.5,11.66V9.09A0,0,0,0,1,8.5,9.09Z" transform="translate(12.41 -4.8) rotate(45)"/><line class="cls-1" x1="12" y1="20.36" x2="12" y2="11.5"/></svg>
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