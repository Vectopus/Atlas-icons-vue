
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="6.26" y1="17.76" x2="6.26" y2="23.5"/><line class="cls-1" x1="4.35" y1="17.76" x2="8.17" y2="17.76"/><polygon class="cls-1" points="9.13 1.5 9.13 12.98 3.39 12.98 3.39 4.37 6.26 1.5 9.13 1.5"/><line class="cls-1" x1="0.52" y1="8.2" x2="3.39" y2="8.2"/><line class="cls-1" x1="9.13" y1="8.2" x2="23.48" y2="8.2"/></svg>
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