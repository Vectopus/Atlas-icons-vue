
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="12" x2="9.13" y2="12"/><line class="cls-1" x1="14.88" y1="12" x2="23.5" y2="12"/><polyline class="cls-1" points="18.71 8.17 14.88 12 18.71 15.83"/><polyline class="cls-1" points="5.29 15.83 9.13 12 5.29 8.17"/><line class="cls-1" x1="12" y1="2.42" x2="12" y2="21.58"/></svg>
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