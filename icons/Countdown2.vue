
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="4.36" x2="12" y2="1.5"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="19.64"/><line class="cls-1" x1="19.64" y1="12" x2="22.5" y2="12"/><line class="cls-1" x1="1.5" y1="12" x2="4.36" y2="12"/><path class="cls-1" d="M22.5,13V12A10.51,10.51,0,1,0,20,18.83"/><path class="cls-1" d="M10.09,10.09V10a1.79,1.79,0,0,1,1.79-1.8h0a2,2,0,0,1,2,2h0a2,2,0,0,1-.59,1.43l-3.23,3.22v1h4.77"/></svg>
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