
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,23.5a4.77,4.77,0,0,1,4.77-4.77h0a4.77,4.77,0,0,1,4.78,4.77"/><circle class="cls-1" cx="6.27" cy="13.95" r="2.86"/><path class="cls-1" d="M13,23.5a4.77,4.77,0,0,1,4.78-4.77h0A4.77,4.77,0,0,1,22.5,23.5"/><circle class="cls-1" cx="17.73" cy="13.95" r="2.86"/><line class="cls-1" x1="12" y1="2.5" x2="12" y2="13.95"/><polyline class="cls-1" points="8.18 6.32 12 2.5 15.82 6.32"/></svg>
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