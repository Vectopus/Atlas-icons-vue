
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="4.36" y1="12" x2="19.64" y2="12"/><polyline class="cls-1" points="8.18 22.5 7.23 12 16.77 12 15.82 22.5"/><path class="cls-1" d="M9.14,10.09A2.86,2.86,0,0,1,12,7.23h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><polyline class="cls-1" points="15.82 5.32 17.73 7.23 17.73 12"/><line class="cls-1" x1="6.27" y1="22.5" x2="17.73" y2="22.5"/></svg>
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