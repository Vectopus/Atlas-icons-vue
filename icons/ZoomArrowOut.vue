
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 1.5 13.98 10.02 13.91 10.09"/><polyline class="cls-1" points="1.5 22.5 10.02 13.98 10.09 13.91"/><polyline class="cls-1" points="10.09 21.55 10.09 13.91 2.46 13.91"/><polyline class="cls-1" points="13.91 2.46 13.91 10.09 21.55 10.09"/><polyline class="cls-1" points="13.91 13.91 13.98 13.98 22.5 22.5"/><polyline class="cls-1" points="10.09 10.09 10.02 10.02 1.5 1.5"/><polyline class="cls-1" points="2.46 10.09 10.09 10.09 10.09 2.46"/><polyline class="cls-1" points="21.55 13.91 13.91 13.91 13.91 21.55"/></svg>
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