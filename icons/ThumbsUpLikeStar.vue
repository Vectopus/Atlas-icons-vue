
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.33,21.51H7.22l1.89.94h5.94a2.82,2.82,0,0,0,2.82-2.55l.68-6.81a1.09,1.09,0,0,0,0-.18h0a1.8,1.8,0,0,0-1.8-1.8H12.89l.1-.2a8,8,0,0,0,.85-3.58h0A1.89,1.89,0,0,0,12,5.44h0a1.89,1.89,0,0,0-1.89,1.89h0a4.56,4.56,0,0,1-1.34,3.23l-1.5,1.49H5.33"/><rect class="cls-1" x="1.55" y="11.11" width="3.78" height="11.34"/><polygon class="cls-1" points="18.56 3.55 19.18 4.79 20.55 4.99 19.56 5.96 19.79 7.33 18.56 6.68 17.34 7.33 17.57 5.96 16.58 4.99 17.95 4.79 18.56 3.55"/></svg>
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