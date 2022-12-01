
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="4" y1="15.5" x2="4" y2="8.5"/><line class="cls-1" x1="20" y1="8.5" x2="20" y2="15.5"/><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><line class="cls-1" x1="7" y1="14.5" x2="9" y2="14.5"/><line class="cls-1" x1="11" y1="14.5" x2="13" y2="14.5"/><line class="cls-1" x1="15" y1="14.5" x2="17" y2="14.5"/><line class="cls-1" x1="7" y1="22.5" x2="9" y2="22.5"/><line class="cls-1" x1="3" y1="22.5" x2="5" y2="22.5"/><line class="cls-1" x1="11" y1="22.5" x2="13" y2="22.5"/><line class="cls-1" x1="15" y1="22.5" x2="17" y2="22.5"/><line class="cls-1" x1="19" y1="22.5" x2="21" y2="22.5"/><line class="cls-1" x1="3" y1="18.5" x2="5" y2="18.5"/><line class="cls-1" x1="19" y1="18.5" x2="21" y2="18.5"/></svg>
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