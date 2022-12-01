
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,1.5V12A6.68,6.68,0,0,1,12,18.68h0A6.68,6.68,0,0,1,5.32,12V1.5"/><line class="cls-1" x1="3.41" y1="22.5" x2="20.59" y2="22.5"/><line class="cls-1" x1="3.41" y1="1.5" x2="7.23" y2="1.5"/><line class="cls-1" x1="16.77" y1="1.5" x2="20.59" y2="1.5"/></svg>
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