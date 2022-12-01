
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="19.12 7.27 22.5 7.27 22.5 17.77 1.5 17.77 1.5 7.27 12.52 7.27"/><circle class="cls-1" cx="15.82" cy="9.18" r="3.82"/><line class="cls-1" x1="4.36" y1="11.09" x2="6.27" y2="11.09"/><line class="cls-1" x1="8.18" y1="11.09" x2="10.09" y2="11.09"/><line class="cls-1" x1="3.41" y1="20.64" x2="3.41" y2="17.77"/><line class="cls-1" x1="20.59" y1="20.64" x2="20.59" y2="17.77"/></svg>
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