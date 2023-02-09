
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10 0.5 13 10.5 8 10.5 5 0.5"/><polyline class="cls-1" points="19 0.5 16 10.5 13 10.5 12 10.5 11 10.5"/><line class="cls-1" x1="14" y1="0.5" x2="12" y2="7.17"/><polygon class="cls-1" points="12 11.5 13.58 14.79 17.1 15.32 14.55 17.88 15.15 21.5 12 19.79 8.85 21.5 9.45 17.88 6.9 15.32 10.42 14.79 12 11.5"/></svg>
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