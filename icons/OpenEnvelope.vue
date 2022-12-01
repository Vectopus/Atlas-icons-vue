
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="10" y1="15.3" x2="3" y2="22.3"/><line class="cls-1" x1="20.6" y1="22.3" x2="13.6" y2="15.3"/><polygon class="cls-1" points="21 9.5 21 22.5 3 22.5 3 9.5 12 1.5 21 9.5"/><polyline class="cls-1" points="21 9.5 12 18.1 3 9.5"/></svg>
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