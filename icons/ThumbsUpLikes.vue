
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="18.68" y="14.86" width="3.82" height="7.64" transform="translate(41.18 37.36) rotate(180)"/><path class="cls-1" d="M14.86,15.82l-.67-1.34a2.82,2.82,0,0,1-.28-1.21h0A1.27,1.27,0,0,1,15.18,12h0a1.28,1.28,0,0,1,1,.51l2.48,3.31v5.73H13.33a1.71,1.71,0,0,1-1.65-1.29l-.58-2.33a1.4,1.4,0,0,1,0-.41h0a1.7,1.7,0,0,1,1.7-1.7Z"/><rect class="cls-1" x="1.5" y="4.36" width="3.82" height="7.64"/><path class="cls-1" d="M9.14,5.32,9.81,4a2.82,2.82,0,0,0,.28-1.21h0A1.27,1.27,0,0,0,8.82,1.5h0A1.28,1.28,0,0,0,7.8,2L5.32,5.32v5.73h5.35a1.71,1.71,0,0,0,1.65-1.29l.58-2.33A1.4,1.4,0,0,0,13,7h0a1.7,1.7,0,0,0-1.7-1.7Z"/></svg>
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