
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.73,21.55V7.23A5.73,5.73,0,0,0,12,1.5H10.09"/><polyline class="cls-1" points="12.96 16.77 17.73 21.55 22.5 16.77"/><path class="cls-1" d="M6.27,2.45V16.77A5.73,5.73,0,0,0,12,22.5h1.91"/><polyline class="cls-1" points="11.04 7.23 6.27 2.46 1.5 7.23"/></svg>
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