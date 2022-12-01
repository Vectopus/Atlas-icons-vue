
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="21.55" x2="12" y2="16.77"/><line class="cls-1" x1="7.23" y1="21.55" x2="16.77" y2="21.55"/><rect class="cls-1" x="1.5" y="2.45" width="21" height="15.27" rx="1.91"/><path class="cls-1" d="M9.3,12a3.82,3.82,0,0,1,5.4,0"/><path class="cls-1" d="M6.75,9.4a7.42,7.42,0,0,1,10.5,0"/><circle class="cls-2" cx="12" cy="13.91" r="0.95"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>