
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="22.5" x2="22.5" y2="1.5"/><polyline class="cls-1" points="15.82 1.5 22.5 1.5 22.5 8.18"/><line class="cls-1" x1="10.09" y1="10.09" x2="1.5" y2="1.5"/><polyline class="cls-1" points="8.18 1.5 1.5 1.5 1.5 8.18"/><line class="cls-1" x1="13.91" y1="13.91" x2="22.5" y2="22.5"/></svg>
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