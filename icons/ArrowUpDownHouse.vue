
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="21" y1="22.5" x2="3" y2="22.5"/><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><line class="cls-1" x1="12" y1="7.5" x2="12" y2="19.5"/><polyline class="cls-1" points="15 16.5 12 19.5 9 16.5"/><polyline class="cls-1" points="9 10.5 12 7.5 15 10.5"/><line class="cls-1" x1="19" y1="18.5" x2="21" y2="18.5"/><line class="cls-1" x1="19" y1="14.5" x2="21" y2="14.5"/><line class="cls-1" x1="19" y1="10.5" x2="21" y2="10.5"/><line class="cls-1" x1="3" y1="14.5" x2="5" y2="14.5"/><line class="cls-1" x1="3" y1="18.5" x2="5" y2="18.5"/><line class="cls-1" x1="3" y1="10.5" x2="5" y2="10.5"/></svg>
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