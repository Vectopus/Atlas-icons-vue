
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="9 6 5 2 1 6"/><polyline class="cls-1" points="18 23 22 19 18 15"/><polyline class="cls-1" points="22 19 5 19 5 2"/><line class="cls-1" x1="19" y1="5" x2="5" y2="19"/><polyline class="cls-1" points="13 5 19 5 19 11"/></svg>
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