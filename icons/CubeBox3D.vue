
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="22.75 8.09 22.75 22.75 8.09 22.75 1.25 15.91 1.25 1.25 15.91 1.25 22.75 8.09"/><polyline class="cls-1" points="8.09 22.75 8.09 8.09 22.75 8.09"/><polyline class="cls-1" points="15.91 1.25 15.91 15.91 1.25 15.91"/><line class="cls-1" x1="1.25" y1="1.25" x2="8.09" y2="8.09"/><line class="cls-1" x1="15.91" y1="15.91" x2="22.75" y2="22.75"/></svg>
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