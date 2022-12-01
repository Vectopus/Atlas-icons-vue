
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.23 6.27 1.5 12 7.23 17.73"/><polyline class="cls-1" points="16.77 17.73 22.5 12 16.77 6.27"/><line class="cls-1" x1="11.05" y1="12" x2="12.95" y2="12"/><line class="cls-1" x1="15.82" y1="12" x2="17.73" y2="12"/><line class="cls-1" x1="6.27" y1="12" x2="8.18" y2="12"/></svg>
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