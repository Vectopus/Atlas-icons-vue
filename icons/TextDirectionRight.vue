
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="10.14" y1="1.5" x2="10.14" y2="15.82"/><line class="cls-1" x1="15.86" y1="1.5" x2="15.86" y2="15.82"/><path class="cls-1" d="M19.68,1.5H8.7A3.35,3.35,0,0,0,5.36,4.84h0A3.34,3.34,0,0,0,8.7,8.18h.54"/><polyline class="cls-1" points="6.32 22.5 2.5 18.68 6.32 14.86"/><line class="cls-1" x1="23.5" y1="18.68" x2="2.5" y2="18.68"/></svg>
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