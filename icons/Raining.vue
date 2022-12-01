
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.2,8.2h-.56a5.88,5.88,0,0,0,.09-.95,5.73,5.73,0,0,0-11.46,0,4.78,4.78,0,0,0,0,9.55H18.2a4.3,4.3,0,1,0,0-8.6Z"/><line class="cls-1" x1="12" y1="23.48" x2="12" y2="18.7"/><line class="cls-1" x1="7.23" y1="22.52" x2="7.23" y2="16.8"/><line class="cls-1" x1="16.77" y1="22.52" x2="16.77" y2="16.8"/></svg>
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