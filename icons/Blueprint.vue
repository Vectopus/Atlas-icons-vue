
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="1.5 4.36 4.36 1.5 7.23 4.36"/><polyline class="cls-1" points="19.64 16.77 22.5 19.64 19.64 22.5"/><polyline class="cls-1" points="22.5 19.64 4.36 19.64 4.36 1.5"/><polyline class="cls-1" points="8.18 1.5 22.5 1.5 22.5 15.82"/><line class="cls-1" x1="19.64" y1="1.5" x2="4.36" y2="16.77"/><line class="cls-1" x1="22.5" y1="4.36" x2="7.23" y2="19.64"/><line class="cls-1" x1="13.91" y1="1.5" x2="4.36" y2="11.05"/><line class="cls-1" x1="22.5" y1="10.09" x2="12.95" y2="19.64"/></svg>
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