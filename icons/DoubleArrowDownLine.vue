
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="6.25" y1="17.73" x2="6.25" y2="0.48"/><polyline class="cls-1" points="1.46 12.94 6.25 17.73 11.04 12.94"/><line class="cls-1" x1="17.75" y1="17.73" x2="17.75" y2="0.48"/><polyline class="cls-1" points="12.96 12.94 17.75 17.73 22.54 12.94"/><line class="cls-1" x1="0.5" y1="22.52" x2="23.5" y2="22.52"/></svg>
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