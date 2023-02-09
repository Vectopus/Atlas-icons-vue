
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="12" x2="10.08" y2="12"/><line class="cls-1" x1="13.92" y1="12" x2="23.5" y2="12"/><polyline class="cls-1" points="19.67 6.25 13.92 12 19.67 17.75"/><polyline class="cls-1" points="4.33 17.75 10.08 12 4.33 6.25"/></svg>
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