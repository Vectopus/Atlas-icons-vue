
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.24,19.6A10.5,10.5,0,1,0,1.5,12a10.44,10.44,0,0,0,3.26,7.6"/><path class="cls-1" d="M17.07,16.34A6.58,6.58,0,0,0,18.68,12,6.68,6.68,0,0,0,5.32,12a6.58,6.58,0,0,0,1.61,4.34"/><path class="cls-1" d="M14.73,12.85a5.08,5.08,0,0,0,.13-.85,2.84,2.84,0,0,0-2.58-2.84,2,2,0,0,0-.56,0A2.84,2.84,0,0,0,9.14,12a5.08,5.08,0,0,0,.13.85"/><polygon class="cls-1" points="17.73 22.5 6.27 22.5 12 13.91 17.73 22.5"/></svg>
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