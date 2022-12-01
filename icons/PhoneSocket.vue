
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="21" rx="1.91"/><polygon class="cls-1" points="17.73 22.5 6.27 22.5 7.23 18.68 16.77 18.68 17.73 22.5"/><line class="cls-1" x1="10.09" y1="18.68" x2="10.09" y2="22.5"/><line class="cls-1" x1="13.91" y1="18.68" x2="13.91" y2="22.5"/><rect class="cls-1" x="7.23" y="6.27" width="9.55" height="7.64"/><line class="cls-1" x1="8.18" y1="4.36" x2="8.18" y2="6.27"/><line class="cls-1" x1="8.18" y1="13.91" x2="8.18" y2="15.82"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="6.27"/><line class="cls-1" x1="12" y1="13.91" x2="12" y2="15.82"/><line class="cls-1" x1="15.82" y1="4.36" x2="15.82" y2="6.27"/><line class="cls-1" x1="15.82" y1="13.91" x2="15.82" y2="15.82"/></svg>
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