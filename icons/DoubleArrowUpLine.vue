
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="17.75" y1="2.44" x2="17.75" y2="19.69"/><polyline class="cls-1" points="22.54 7.23 17.75 2.44 12.96 7.23"/><line class="cls-1" x1="6.25" y1="2.44" x2="6.25" y2="19.69"/><polyline class="cls-1" points="11.04 7.23 6.25 2.44 1.46 7.23"/><line class="cls-1" x1="0.5" y1="22.56" x2="23.5" y2="22.56"/></svg>
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