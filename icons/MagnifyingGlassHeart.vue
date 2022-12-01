
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12.26,6.51a2.64,2.64,0,0,0-2.17,1.12A2.64,2.64,0,0,0,7.92,6.51,2.55,2.55,0,0,0,5.32,9c0,3.76,4.77,5.84,4.77,5.84S14.86,12.78,14.86,9A2.55,2.55,0,0,0,12.26,6.51Z"/><circle class="cls-1" cx="10.09" cy="10.09" r="8.59"/><line class="cls-1" x1="22.5" y1="22.5" x2="15.82" y2="15.82"/></svg>
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