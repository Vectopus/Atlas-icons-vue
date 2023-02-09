
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.28" y="18.68" width="11.45" height="3.82"/><polygon class="cls-1" points="18.68 6.28 5.32 6.28 7.23 18.68 16.77 18.68 18.68 6.28"/><line class="cls-1" x1="3.41" y1="6.28" x2="20.59" y2="6.28"/><line class="cls-1" x1="3.41" y1="22.5" x2="20.59" y2="22.5"/><polyline class="cls-1" points="7.2 6.19 7.2 3.42 9.13 1.5"/><polyline class="cls-1" points="16.78 6.28 16.78 3.52 14.86 1.6"/><polygon class="cls-1" points="13.91 10.1 12 12.01 10.09 10.1 10.09 6.28 13.91 6.28 13.91 10.1"/></svg>
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