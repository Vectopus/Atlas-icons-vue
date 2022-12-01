
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="19.64 8.18 22.5 8.18 22.5 15.82 1.5 15.82 1.5 8.18 12 8.18"/><circle class="cls-1" cx="15.82" cy="8.18" r="3.82"/><line class="cls-1" x1="4.36" y1="19.64" x2="4.36" y2="15.82"/><line class="cls-1" x1="19.64" y1="19.64" x2="19.64" y2="15.82"/><line class="cls-1" x1="4.36" y1="12" x2="6.27" y2="12"/><line class="cls-1" x1="8.18" y1="12" x2="10.09" y2="12"/></svg>
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