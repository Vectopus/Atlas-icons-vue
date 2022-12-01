
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,22.5h0A11.87,11.87,0,0,1,2.45,10.86V3.41L12,1.5l9.55,1.91v7.45A11.87,11.87,0,0,1,12,22.5Z"/><circle class="cls-1" cx="12" cy="12" r="4.77"/><line class="cls-1" x1="15.38" y1="8.62" x2="8.66" y2="15.34"/></svg>
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