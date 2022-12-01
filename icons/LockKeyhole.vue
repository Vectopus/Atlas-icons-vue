
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="10.09" width="13.36" height="12.41"/><path class="cls-1" d="M12,1.5h0a4.77,4.77,0,0,1,4.77,4.77v3.82a0,0,0,0,1,0,0H7.23a0,0,0,0,1,0,0V6.27A4.77,4.77,0,0,1,12,1.5Z"/><circle class="cls-1" cx="12" cy="14.86" r="0.95"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="15.82"/></svg>
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