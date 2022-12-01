
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="18.68" width="15.27" height="3.82"/><line class="cls-1" x1="2.45" y1="22.5" x2="21.55" y2="22.5"/><path class="cls-1" d="M12,1.5h0a6.68,6.68,0,0,1,6.68,6.68v10.5a0,0,0,0,1,0,0H5.32a0,0,0,0,1,0,0V8.18A6.68,6.68,0,0,1,12,1.5Z"/><path class="cls-1" d="M8.66,7.79h2.46A4.23,4.23,0,0,1,15.34,12v2.46a0,0,0,0,1,0,0H12.89a4.23,4.23,0,0,1-4.23-4.23V7.79a0,0,0,0,1,0,0Z" transform="translate(11.38 -5.23) rotate(45)"/><line class="cls-1" x1="12" y1="18.55" x2="12" y2="10.09"/></svg>
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