
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,10.09C20.59,16.77,12,22.5,12,22.5S3.41,16.77,3.41,10.09a8.59,8.59,0,0,1,17.18,0Z"/><line class="cls-1" x1="9.14" y1="6.27" x2="9.14" y2="13.91"/><line class="cls-1" x1="14.86" y1="6.27" x2="14.86" y2="13.91"/><line class="cls-1" x1="9.14" y1="10.09" x2="14.86" y2="10.09"/></svg>
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