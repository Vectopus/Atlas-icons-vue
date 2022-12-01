
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="7.23" x2="12" y2="15.82"/><line class="cls-1" x1="10.09" y1="15.82" x2="13.91" y2="15.82"/><line class="cls-1" x1="10.09" y1="9.14" x2="12.95" y2="9.14"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="1.5"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="19.64"/><line class="cls-1" x1="19.64" y1="12" x2="22.5" y2="12"/><line class="cls-1" x1="1.5" y1="12" x2="4.36" y2="12"/><path class="cls-1" d="M22.5,13V12A10.51,10.51,0,1,0,20,18.83"/></svg>
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