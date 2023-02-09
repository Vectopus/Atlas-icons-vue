
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10.09 1.5 12.96 11.04 8.18 11.04 5.32 1.5"/><polyline class="cls-1" points="18.68 1.5 15.82 11.04 12.96 11.04 12 11.04 11.04 11.04"/><line class="cls-1" x1="13.91" y1="1.5" x2="12" y2="7.87"/><circle class="cls-2" cx="12" cy="17.73" r="4.77"/><line class="cls-1" x1="12" y1="10.09" x2="12" y2="12.95"/><line class="cls-1" x1="12" y1="15.82" x2="12" y2="19.64"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>