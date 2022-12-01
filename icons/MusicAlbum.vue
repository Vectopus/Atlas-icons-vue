
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.36" width="15.27" height="15.27"/><path class="cls-1" d="M22.5,12a6.67,6.67,0,0,1-5.73,6.61V5.39A6.67,6.67,0,0,1,22.5,12Z"/><circle class="cls-1" cx="6.27" cy="14.86" r="0.95"/><circle class="cls-1" cx="12" cy="13.91" r="0.95"/><polyline class="cls-1" points="12.96 13.91 12.96 8.18 7.23 9.14 7.23 14.86"/></svg>
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