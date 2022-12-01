
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="21.65" y1="18.92" x2="21.65" y2="4.38"/><line class="cls-1" x1="1.65" y1="18.92" x2="1.65" y2="4.38"/><path class="cls-1" d="M1.65,18.92c0,1,1.81,1.8,4.54,2.29V6.67C3.46,6.18,1.65,5.34,1.65,4.38c0-1.51,4.47-2.73,10-2.73s10,1.22,10,2.73c0,1-1.81,1.8-4.55,2.29V21.21c2.74-.49,4.55-1.32,4.55-2.29"/><circle class="cls-1" cx="11.65" cy="8.92" r="1.82"/><polygon class="cls-1" points="9.83 12.56 13.47 12.56 13.47 14.51 12.56 21.65 10.74 21.65 9.83 14.38 9.83 12.56"/></svg>
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