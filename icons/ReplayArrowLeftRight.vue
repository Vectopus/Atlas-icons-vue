
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.45,17.73H16.77A5.73,5.73,0,0,0,22.5,12V10.09"/><polyline class="cls-1" points="7.23 12.96 2.46 17.73 7.23 22.5"/><path class="cls-1" d="M21.55,6.27H7.23A5.73,5.73,0,0,0,1.5,12v1.91"/><polyline class="cls-1" points="16.77 11.04 21.55 6.27 16.77 1.5"/></svg>
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