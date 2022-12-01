
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="10.09" y1="1.5" x2="13.91" y2="1.5"/><polygon class="cls-1" points="17.73 22.5 6.27 22.5 2.46 12 12 10.09 21.55 12 17.73 22.5"/><polyline class="cls-1" points="5.32 11.43 7.23 5.32 16.77 5.32 18.68 11.43"/><line class="cls-1" x1="12" y1="5.32" x2="12" y2="1.5"/><line class="cls-1" x1="12" y1="12.95" x2="12" y2="22.5"/></svg>
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