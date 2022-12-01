
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 3.41 1.5 12 1.5 15.82 22.5 15.82 22.5 12 12 3.41"/><polyline class="cls-1" points="10.69 19.64 1.5 19.64 1.5 15.82 5.44 15.82 18.57 15.82 22.5 15.82 22.5 19.64 13.32 19.64"/><line class="cls-1" x1="1.5" y1="12" x2="22.5" y2="12"/><polyline class="cls-1" points="5.44 15.82 10.69 19.64 12 20.59 13.32 19.64 18.57 15.82"/></svg>
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