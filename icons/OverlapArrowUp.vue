
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10.09 6.32 6.27 2.5 2.46 6.32"/><polyline class="cls-1" points="21.55 6.32 17.73 2.5 13.91 6.32"/><path class="cls-1" d="M17.73,23.5V20.36a5.73,5.73,0,0,0-3.17-5.12L9.44,12.67A5.73,5.73,0,0,1,6.27,7.55v-5"/><path class="cls-1" d="M6.27,23.5V20.36a5.73,5.73,0,0,1,3.17-5.12l5.12-2.57a5.73,5.73,0,0,0,3.17-5.12v-5"/></svg>
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