
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><polygon class="cls-1" points="14.2 8.18 9.8 8.18 7.59 12 9.8 15.82 14.2 15.82 16.41 12 14.2 8.18"/><line class="cls-2" x1="19.64" y1="12" x2="16.41" y2="12"/><line class="cls-2" x1="7.59" y1="12" x2="4.36" y2="12"/><line class="cls-2" x1="15.82" y1="5.39" x2="14.2" y2="8.18"/><line class="cls-2" x1="9.8" y1="15.82" x2="8.18" y2="18.62"/><line class="cls-2" x1="9.8" y1="8.18" x2="8.18" y2="5.39"/><line class="cls-2" x1="15.82" y1="18.62" x2="14.2" y2="15.82"/></svg>
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