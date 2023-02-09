
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="2.45" y1="20.59" x2="21.55" y2="20.59"/><polyline class="cls-1" points="2.46 7.23 4.36 13.91 4.36 20.59 19.64 20.59 19.64 13.91 21.55 7.23"/><polyline class="cls-1" points="21.55 7.23 15.82 10.09 12 5.32"/><polyline class="cls-1" points="12 5.32 8.18 10.09 2.46 7.23"/><ellipse class="cls-1" cx="12" cy="14.86" rx="1.91" ry="2.86"/><line class="cls-1" x1="15.82" y1="14.86" x2="19.64" y2="14.86"/><line class="cls-1" x1="8.18" y1="14.86" x2="4.36" y2="14.86"/><circle class="cls-1" cx="12" cy="4.36" r="0.95"/><circle class="cls-1" cx="2.45" cy="6.27" r="0.95"/><circle class="cls-1" cx="21.55" cy="6.27" r="0.95"/></svg>
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