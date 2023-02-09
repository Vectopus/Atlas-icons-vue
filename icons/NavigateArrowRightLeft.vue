
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="18 9 22 5 18 1"/><polyline class="cls-1" points="6 15 2 19 6 23"/><path class="cls-1" d="M22,5H5.5A3.5,3.5,0,0,0,2,8.5H2A3.5,3.5,0,0,0,5.5,12h13A3.5,3.5,0,0,1,22,15.5h0A3.5,3.5,0,0,1,18.5,19H2"/></svg>
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