
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.38,20.62H8.62a6.92,6.92,0,0,1-6.2-3.83H21.58A6.92,6.92,0,0,1,15.38,20.62Z"/><line class="cls-1" x1="0.5" y1="16.79" x2="23.5" y2="16.79"/><path class="cls-1" d="M11.6,7.21h.8a8.22,8.22,0,0,1,8.22,8.22v1.36a0,0,0,0,1,0,0H3.37a0,0,0,0,1,0,0V15.43A8.22,8.22,0,0,1,11.6,7.21Z"/><line class="cls-1" x1="12" y1="5.29" x2="12" y2="7.21"/><circle class="cls-1" cx="12" cy="4.33" r="0.96"/></svg>
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