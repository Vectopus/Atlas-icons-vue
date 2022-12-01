
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="17.65" y1="3.55" x2="17.65" y2="14.85"/><polyline class="cls-1" points="12.83 7.2 17.65 2.38 22.47 7.2"/><path class="cls-1" d="M15.56,22.38a2.51,2.51,0,0,0,2.09-1.13,2.51,2.51,0,0,0,4.6-1.38c0-3.77-4.6-5-4.6-5s-4.6,1.25-4.6,5A2.51,2.51,0,0,0,15.56,22.38Z"/><line class="cls-1" x1="6.35" y1="21.21" x2="6.35" y2="9.91"/><polyline class="cls-1" points="11.17 17.56 6.35 22.38 1.53 17.56"/><path class="cls-1" d="M8.44,2.38A2.52,2.52,0,0,0,6.35,3.5a2.51,2.51,0,0,0-4.6,1.39c0,3.77,4.6,5,4.6,5s4.6-1.25,4.6-5A2.51,2.51,0,0,0,8.44,2.38Z"/></svg>
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