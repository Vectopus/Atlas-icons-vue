
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="12.32 11.98 11.04 15.8 12.96 15.8 11.68 19.63"/><path class="cls-1" d="M16.78,10.07V22.5H7.22V10.07l.89-.45A1.85,1.85,0,0,0,9.13,8h0a1.85,1.85,0,0,0-.54-1.31l-.42-.41V4.33h0a1.92,1.92,0,0,0,1.92-1.92h3.82a1.92,1.92,0,0,0,1.92,1.92h0V6.24l-.42.41A1.85,1.85,0,0,0,14.87,8h0a1.85,1.85,0,0,0,1,1.66Z"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.41"/></svg>
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