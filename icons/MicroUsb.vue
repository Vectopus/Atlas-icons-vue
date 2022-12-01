
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><path class="cls-1" d="M9.14,8.18h5.73A3.82,3.82,0,0,1,18.68,12v3.82a0,0,0,0,1,0,0H5.32a0,0,0,0,1,0,0V12A3.82,3.82,0,0,1,9.14,8.18Z"/><line class="cls-1" x1="8.18" y1="12" x2="15.82" y2="12"/></svg>
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