
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><line class="cls-1" x1="13.91" y1="12" x2="5.32" y2="12"/><polyline class="cls-1" points="13.91 7.23 18.68 12 13.91 16.77"/><polyline class="cls-1" points="9.14 7.23 13.91 12 9.14 16.77"/></svg>
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