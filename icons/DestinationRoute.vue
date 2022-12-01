
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.11,5.08c0,2.39-3.81,6-3.81,6s-3.82-3.58-3.82-6A3.7,3.7,0,0,1,5.3,1.5,3.7,3.7,0,0,1,9.11,5.08Z"/><circle class="cls-2" cx="5.3" cy="5.32" r="0.95"/><path class="cls-1" d="M4.34,13h4.3A2.39,2.39,0,0,1,11,15.34h0a2.39,2.39,0,0,1-2.38,2.39H3.86a2.39,2.39,0,0,0-2.38,2.38h0A2.39,2.39,0,0,0,3.86,22.5H17.7"/><line class="cls-1" x1="16.75" y1="8.18" x2="16.75" y2="20.59"/><polygon class="cls-1" points="16.75 15.82 21.52 12.96 16.75 10.09 16.75 15.82"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>