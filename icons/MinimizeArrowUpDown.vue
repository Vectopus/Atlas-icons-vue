
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="23.5" x2="12" y2="13.92"/><line class="cls-1" x1="12" y1="10.08" x2="12" y2="0.5"/><polyline class="cls-1" points="6.25 4.33 12 10.08 17.75 4.33"/><polyline class="cls-1" points="17.75 19.67 12 13.92 6.25 19.67"/></svg>
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