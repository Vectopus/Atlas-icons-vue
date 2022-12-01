
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8.18" y1="22.5" x2="9.14" y2="17.73"/><line class="cls-1" x1="5.32" y1="22.5" x2="18.68" y2="22.5"/><rect class="cls-1" x="1.5" y="1.5" width="21" height="16.23" rx="1.91"/><line class="cls-1" x1="15.75" y1="22.5" x2="14.8" y2="17.73"/><line class="cls-1" x1="1.5" y1="13.91" x2="22.5" y2="13.91"/></svg>
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