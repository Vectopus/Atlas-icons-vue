
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.3,1.5h7.16A5.25,5.25,0,0,1,17.7,6.75v0A5.25,5.25,0,0,1,12.45,12H5.3a0,0,0,0,1,0,0V1.5a0,0,0,0,1,0,0Z"/><path class="cls-1" d="M5.3,12h9.07a5.25,5.25,0,0,1,5.25,5.25v0a5.25,5.25,0,0,1-5.25,5.25H5.3a0,0,0,0,1,0,0V12A0,0,0,0,1,5.3,12Z"/><line class="cls-1" x1="3.39" y1="1.5" x2="5.3" y2="1.5"/><line class="cls-1" x1="3.39" y1="22.5" x2="5.3" y2="22.5"/></svg>
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