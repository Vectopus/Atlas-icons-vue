
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="17.73" r="4.77"/><line class="cls-2" x1="12" y1="15.82" x2="12" y2="19.64"/><line class="cls-2" x1="4.36" y1="1.5" x2="19.64" y2="1.5"/><polygon class="cls-2" points="17.73 9.14 12 12 6.27 9.14 6.27 1.5 17.73 1.5 17.73 9.14"/><polyline class="cls-2" points="10.09 11.04 10.09 1.5 13.91 1.5 13.91 11.04"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>