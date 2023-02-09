
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="9 6 5 2 1 6"/><polyline class="cls-1" points="23 6 19 2 15 6"/><path class="cls-1" d="M12,24V18.64A4.83,4.83,0,0,0,8.5,14h0A4.83,4.83,0,0,1,5,9.36V2"/><path class="cls-1" d="M12,24V18.64A4.83,4.83,0,0,1,15.5,14h0A4.83,4.83,0,0,0,19,9.36V2"/></svg>
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