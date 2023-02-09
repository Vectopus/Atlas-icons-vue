
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="8.18" y="12.95" width="7.64" height="9.55"/><rect class="cls-1" x="15.82" y="16.77" width="6.68" height="5.73"/><rect class="cls-1" x="1.5" y="18.68" width="6.68" height="3.82"/><path class="cls-1" d="M9.14,1.5h5.73a0,0,0,0,1,0,0V4.36A2.86,2.86,0,0,1,12,7.23h0A2.86,2.86,0,0,1,9.14,4.36V1.5a0,0,0,0,1,0,0Z"/><line class="cls-1" x1="9.14" y1="10.09" x2="14.86" y2="10.09"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="10.09"/><line class="cls-1" x1="17.73" y1="3.41" x2="14.86" y2="3.41"/><line class="cls-1" x1="9.14" y1="3.41" x2="6.27" y2="3.41"/></svg>
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