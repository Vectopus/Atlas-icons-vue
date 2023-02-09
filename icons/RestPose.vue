
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="15.85" x2="23.5" y2="15.85"/><circle class="cls-1" cx="3.38" cy="11.06" r="1.92"/><path class="cls-1" d="M15.83,10.1H8.65a1.44,1.44,0,0,0-1.44,1.44h0A1.43,1.43,0,0,0,8.65,13H22.54V10.1"/></svg>
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