
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.22,23.5A4.78,4.78,0,0,1,12,18.72h0a4.78,4.78,0,0,1,4.78,4.78"/><circle class="cls-1" cx="12" cy="13.93" r="2.87"/><path class="cls-1" d="M1.48,9.15V3.41A1.91,1.91,0,0,1,3.39,1.5h0A1.91,1.91,0,0,1,5.3,3.41V9.15"/><line class="cls-1" x1="1.48" y1="5.33" x2="5.3" y2="5.33"/><path class="cls-1" d="M18.7,1.5h1.91a1.91,1.91,0,0,1,1.91,1.91v0a1.91,1.91,0,0,1-1.91,1.91H18.7a0,0,0,0,1,0,0V1.5A0,0,0,0,1,18.7,1.5Z"/><path class="cls-1" d="M18.7,5.33h1.91a1.91,1.91,0,0,1,1.91,1.91v0a1.91,1.91,0,0,1-1.91,1.91H18.7a0,0,0,0,1,0,0V5.33A0,0,0,0,1,18.7,5.33Z"/></svg>
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