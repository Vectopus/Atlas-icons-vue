
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,22.5h0A11.87,11.87,0,0,1,2.45,10.86V3.41L12,1.5l9.55,1.91v7.45A11.87,11.87,0,0,1,12,22.5Z"/><circle class="cls-1" cx="12" cy="10.09" r="0.95"/><line class="cls-1" x1="12" y1="13.91" x2="12" y2="11.05"/><circle class="cls-1" cx="12" cy="11.05" r="5.73"/></svg>
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