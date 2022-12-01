
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="17.18" height="21" rx="1.91"/><line class="cls-1" x1="9.14" y1="19.64" x2="11.05" y2="19.64"/><path class="cls-2" d="M22,22.5l-.47-2.86a1,1,0,1,1,1.9,0L23,22.5a.49.49,0,0,1-1,0Z"/><line class="cls-3" x1="22.5" y1="1.5" x2="22.5" y2="19.64"/></svg>
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
    .cls-1,.cls-3{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}.cls-3{stroke-linecap:round;}
</style>