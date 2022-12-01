
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="1.5" width="11.45" height="21" rx="2.86"/><polyline class="cls-1" points="17.73 8.18 12.96 12.96 6.27 8.18"/><line class="cls-1" x1="6.27" y1="8.18" x2="17.73" y2="8.18"/><rect class="cls-1" x="9.14" y="4.36" width="5.73" height="3.82" rx="1.91"/></svg>
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