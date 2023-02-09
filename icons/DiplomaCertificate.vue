
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="13.91 17.25 22.5 17.25 22.5 1.98 1.5 1.98 1.5 17.25 10.09 17.25"/><circle class="cls-1" cx="12" cy="15.34" r="2.86"/><polyline class="cls-1" points="13.91 17.47 13.91 19.16 13.91 22.02 12 21.07 10.09 22.02 10.09 19.16 10.09 17.47"/><line class="cls-1" x1="5.32" y1="5.8" x2="18.68" y2="5.8"/><line class="cls-1" x1="5.32" y1="9.61" x2="18.68" y2="9.61"/></svg>
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