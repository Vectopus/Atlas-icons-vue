
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,3.41a31.45,31.45,0,0,0,7.64-1H22.5v19.1H19.64a31.45,31.45,0,0,0-7.64-1,31.45,31.45,0,0,0-7.64,1H1.5V2.45H4.36A31.45,31.45,0,0,0,12,3.41Z"/><rect class="cls-1" x="9.14" y="3.41" width="9.55" height="17.18" transform="translate(1.91 25.91) rotate(-90)"/><line class="cls-1" x1="5.32" y1="12.95" x2="22.5" y2="12.95"/><path class="cls-1" d="M13.91,10.09h0Z"/></svg>
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