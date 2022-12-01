
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20.59 13.91 20.59 22.5 1.5 22.5 1.5 3.41 10.09 3.41"/><polyline class="cls-1" points="13.91 1.5 22.5 1.5 22.5 10.09"/><line class="cls-1" x1="22.5" y1="1.5" x2="10.09" y2="13.91"/></svg>
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