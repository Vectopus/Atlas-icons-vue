
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.07,12H6.72A5.26,5.26,0,0,1,1.46,6.74h0A5.25,5.25,0,0,1,6.72,1.48H22.5"/><path class="cls-1" d="M13.89,12h3.35a5.27,5.27,0,0,1,5.26,5.26h0a5.26,5.26,0,0,1-5.26,5.26H.5"/><polyline class="cls-1" points="17.72 8.17 13.89 12 17.72 15.83"/><polyline class="cls-1" points="6.24 15.83 10.06 12 6.24 8.17"/></svg>
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