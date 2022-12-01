
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20.59 13.91 20.59 22.5 1.5 22.5 1.5 3.41 10.09 3.41"/><polyline class="cls-1" points="17.73 14.86 9.14 14.86 9.14 6.27"/><line class="cls-1" x1="9.14" y1="14.86" x2="22.5" y2="1.5"/></svg>
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