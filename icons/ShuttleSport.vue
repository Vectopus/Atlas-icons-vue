
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="11.05" width="21" height="9.55" rx="2.86"/><path class="cls-1" d="M5.32,5.32h0A1.91,1.91,0,0,0,7.23,7.23H13v3.82h6.69L17.73,3.41H7.23A1.9,1.9,0,0,0,5.32,5.32Z"/><line class="cls-1" x1="1.5" y1="15.82" x2="22.5" y2="15.82"/></svg>
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