
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="17.64 6.27 21.55 6.27 21.55 18.68 2.46 18.68 2.46 6.27 6.36 6.27"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"/><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"/><circle class="cls-1" cx="12" cy="7.23" r="5.73"/><line class="cls-1" x1="6.27" y1="7.23" x2="17.73" y2="7.23"/><ellipse class="cls-1" cx="12" cy="7.23" rx="1.91" ry="5.73"/></svg>
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