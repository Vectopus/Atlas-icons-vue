
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="7.3" width="3.82" height="7.64" rx="1.91"/><rect class="cls-1" x="18.68" y="7.3" width="3.82" height="7.64" rx="1.91"/><line class="cls-1" x1="5.32" y1="4.43" x2="5.32" y2="22.57"/><line class="cls-1" x1="18.68" y1="4.43" x2="18.68" y2="22.57"/><line class="cls-1" x1="5.32" y1="11.11" x2="18.68" y2="11.11"/><line class="cls-1" x1="8.18" y1="17.8" x2="15.82" y2="17.8"/><line class="cls-1" x1="12" y1="22.57" x2="12" y2="17.8"/><line class="cls-1" x1="3.41" y1="22.57" x2="7.23" y2="22.57"/><line class="cls-1" x1="10.09" y1="22.57" x2="13.91" y2="22.57"/><line class="cls-1" x1="16.77" y1="22.57" x2="20.59" y2="22.57"/></svg>
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