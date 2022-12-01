
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="14.39" y1="18.68" x2="7.7" y2="18.68"/><path class="cls-1" d="M3.89,18.68H1.5V5.32A1.91,1.91,0,0,1,3.41,3.41H17.15A1.9,1.9,0,0,1,19,4.9L20.59,12,22.5,13v5.73H18.2"/><circle class="cls-1" cx="16.3" cy="18.68" r="1.91"/><circle class="cls-1" cx="5.8" cy="18.68" r="1.91"/><polyline class="cls-1" points="15.82 6.27 15.82 12 20.59 12"/><line class="cls-1" x1="5.32" y1="10.09" x2="11.05" y2="10.09"/><line class="cls-1" x1="8.18" y1="7.23" x2="8.18" y2="12.95"/><line class="cls-1" x1="20.59" y1="14.86" x2="22.5" y2="14.86"/></svg>
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