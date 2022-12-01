
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="21.55 22.5 2.46 22.5 6.48 17.68 12 11.04 17.52 17.68 21.55 22.5"/><rect class="cls-1" x="12" y="1.5" width="5.73" height="4.77"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="5.32"/><polyline class="cls-1" points="8.28 15.51 11.04 17.73 12 16.77 13.91 18.68 16.53 16.5"/></svg>
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