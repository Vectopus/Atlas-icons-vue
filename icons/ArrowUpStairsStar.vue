
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="0.5 22.58 8.17 22.58 8.17 17.79 15.83 17.79 15.83 12.04 23.5 12.04"/><polygon class="cls-1" points="18.71 3.42 19.33 4.68 20.72 4.88 19.72 5.86 19.95 7.25 18.71 6.59 17.46 7.25 17.7 5.86 16.69 4.88 18.09 4.68 18.71 3.42"/><line class="cls-1" x1="2.42" y1="16.83" x2="10.08" y2="9.17"/><polyline class="cls-1" points="6.25 9.17 10.08 9.17 10.08 13"/></svg>
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