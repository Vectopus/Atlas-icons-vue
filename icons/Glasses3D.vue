
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,13.91H1.5V22.5h8.65l.63-1.95A1.29,1.29,0,0,1,12,19.64h0a1.3,1.3,0,0,1,1.24.88l.67,2H22.5V13.91Z"/><path class="cls-1" d="M7.23,18.68H5.32v-.95H8.18A1,1,0,0,1,7.23,18.68Z"/><path class="cls-1" d="M18.68,18.68H16.77a1,1,0,0,1-.95-.95h2.86Z"/><path class="cls-1" d="M1.5,13.91V5.32A3.82,3.82,0,0,1,5.32,1.5H7.23"/><path class="cls-1" d="M22.5,13.91V5.32A3.82,3.82,0,0,0,18.68,1.5H16.77"/></svg>
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