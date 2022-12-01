
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="16.77 8.18 16.77 22.5 3.41 22.5 3.41 5.32 16.77 5.32 16.77 8.18"/><line class="cls-1" x1="6.27" y1="13.91" x2="13.91" y2="13.91"/><line class="cls-1" x1="6.27" y1="10.09" x2="13.91" y2="10.09"/><line class="cls-1" x1="6.27" y1="17.73" x2="12" y2="17.73"/><polyline class="cls-1" points="20.59 19.64 20.59 4.36 20.59 1.5 6.27 1.5"/></svg>
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