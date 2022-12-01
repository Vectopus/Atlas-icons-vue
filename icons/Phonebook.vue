
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.37" y="1.48" width="19.13" height="21.04"/><line class="cls-1" x1="0.5" y1="6.26" x2="6.24" y2="6.26"/><line class="cls-1" x1="0.5" y1="12" x2="6.24" y2="12"/><line class="cls-1" x1="0.5" y1="17.74" x2="6.24" y2="17.74"/><circle class="cls-1" cx="13.89" cy="9.13" r="2.87"/><path class="cls-1" d="M13.89,12h0a3.83,3.83,0,0,1,3.83,3.83v1.91a0,0,0,0,1,0,0H10.07a0,0,0,0,1,0,0V15.83A3.83,3.83,0,0,1,13.89,12Z"/></svg>
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