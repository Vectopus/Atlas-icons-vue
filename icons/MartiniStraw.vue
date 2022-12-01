
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12.02 15.82 4.39 8.18 19.66 8.18 12.02 15.82"/><line class="cls-1" x1="12.02" y1="22.5" x2="12.02" y2="14.86"/><line class="cls-1" x1="15.84" y1="22.5" x2="8.2" y2="22.5"/><polyline class="cls-1" points="13.49 8.18 15.84 1.5 20.61 1.5"/></svg>
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