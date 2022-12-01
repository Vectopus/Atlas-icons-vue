
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><polyline class="cls-1" points="20 8.5 20 22.5 4 22.5 4 20.5 9 15.5 11 17.5 16 12.5"/><polyline class="cls-1" points="12 12.5 16 12.5 16 16.5"/><line class="cls-1" x1="4" y1="8.5" x2="4" y2="16.5"/></svg>
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