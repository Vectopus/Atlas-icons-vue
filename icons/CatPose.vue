
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.11" cy="10.57" r="2.39"/><path class="cls-1" d="M18.67,18.7H15.8V9.42a4.1,4.1,0,0,0-.69-2.28h0A4.11,4.11,0,0,0,11.69,5.3h-.18a4.07,4.07,0,0,0-2.57.91L6.24,8.36a2.59,2.59,0,0,0-1,2h0a2.54,2.54,0,0,0,.34,1.27l3.49,6.11v1H.5"/><path class="cls-1" d="M13.89,9.13H12.36A3.87,3.87,0,0,0,10,10L6.24,13"/></svg>
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