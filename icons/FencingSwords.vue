
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.75,15.48h0A3.54,3.54,0,0,1,10.29,19v0a0,0,0,0,1,0,0H3.21a0,0,0,0,1,0,0v0a3.54,3.54,0,0,1,3.54-3.54Z" transform="translate(14.17 0.28) rotate(45)"/><line class="cls-1" x1="23" y1="1" x2="8" y2="16"/><line class="cls-1" x1="5.5" y1="18.5" x2="1" y2="23"/><line class="cls-1" x1="1" y1="18" x2="3" y2="16"/><path class="cls-1" d="M13.71,15.48h7.07a0,0,0,0,1,0,0v0A3.54,3.54,0,0,1,17.25,19h0a3.54,3.54,0,0,1-3.54-3.54v0a0,0,0,0,1,0,0Z" transform="translate(41.65 17.25) rotate(135)"/><line class="cls-1" x1="16" y1="16" x2="1" y2="1"/><line class="cls-1" x1="23" y1="23" x2="18.5" y2="18.5"/><line class="cls-1" x1="23" y1="18" x2="21" y2="16"/></svg>
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