
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="8.18" cy="5.36" r="1.91"/><circle class="cls-1" cx="15.82" cy="5.36" r="1.91"/><line class="cls-1" x1="8.18" y1="7.27" x2="15.82" y2="7.27"/><polyline class="cls-1" points="20.59 7.27 22.5 7.27 22.5 22.55 1.5 22.55 1.5 7.27 3.41 7.27"/><polyline class="cls-1" points="1.5 7.27 12 17.77 22.5 7.27"/><line class="cls-1" x1="9.14" y1="14.91" x2="1.5" y2="22.55"/><line class="cls-1" x1="22.5" y1="22.55" x2="14.86" y2="14.91"/></svg>
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