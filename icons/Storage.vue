
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="16.77" width="15.27" height="5.73" rx="1.91"/><path class="cls-1" d="M19.64,18.68V3.41A1.91,1.91,0,0,0,17.73,1.5H6.27A1.91,1.91,0,0,0,4.36,3.41V18.68"/><line class="cls-1" x1="13.91" y1="19.64" x2="17.73" y2="19.64"/><circle class="cls-2" cx="7.23" cy="19.64" r="0.95"/></svg>
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