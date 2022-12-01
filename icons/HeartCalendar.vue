
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.74,12.93A2.23,2.23,0,0,0,12,13.7a2.23,2.23,0,0,0-1.74-.77,1.93,1.93,0,0,0-2.08,1.72c0,2.58,3.82,4,3.82,4s3.82-1.43,3.82-4A1.93,1.93,0,0,0,13.74,12.93Z"/><rect class="cls-1" x="1.5" y="3.39" width="21" height="5.73"/><rect class="cls-1" x="1.5" y="9.11" width="21" height="13.36"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="6.25"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="6.25"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="6.25"/></svg>
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