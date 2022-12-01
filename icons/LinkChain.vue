
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.57,5.8l2.71-2.72a5.4,5.4,0,0,1,7.64,7.64L18.2,13.43"/><path class="cls-1" d="M5.8,10.57,3.08,13.28a5.4,5.4,0,0,0,7.64,7.64l2.71-2.72"/><line class="cls-1" x1="16.77" y1="7.23" x2="7.23" y2="16.77"/></svg>
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