
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="16.77" width="18.14" height="5.73" rx="1.91"/><circle class="cls-1" cx="20.59" cy="15.82" r="1.91"/><path class="cls-1" d="M21.55,14.17,20.72,8.7a8.46,8.46,0,0,0-8.36-7.2h0A8.46,8.46,0,0,0,4,8.42L2.45,16.94"/><line class="cls-1" x1="15.82" y1="6.27" x2="17.73" y2="16.77"/></svg>
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