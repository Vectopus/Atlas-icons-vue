
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><path class="cls-1" d="M8.18,22.5a3.82,3.82,0,0,1,7.64,0"/><circle class="cls-1" cx="12" cy="5.32" r="3.82"/><polyline class="cls-1" points="10.29 8.73 10.65 10.09 13.35 10.09 13.71 8.73"/><line class="cls-1" x1="12" y1="10.09" x2="12" y2="18.68"/></svg>
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