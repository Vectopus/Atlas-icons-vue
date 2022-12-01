
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="16.77" r="5.73"/><polygon class="cls-1" points="12 15.82 11.28 16.77 12 16.77 12 15.82"/><polygon class="cls-1" points="12 17.73 12.72 16.77 12 16.77 12 17.73"/><path class="cls-1" d="M5.32,1.5H7.23A4.77,4.77,0,0,1,12,6.27v0a0,0,0,0,1,0,0H10.09A4.77,4.77,0,0,1,5.32,1.5v0A0,0,0,0,1,5.32,1.5Z"/><path class="cls-1" d="M16.77,2.45h1.91a0,0,0,0,1,0,0v0a4.77,4.77,0,0,1-4.77,4.77H12a0,0,0,0,1,0,0v0A4.77,4.77,0,0,1,16.77,2.45Z" transform="translate(30.68 9.68) rotate(-180)"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="6.27"/></svg>
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