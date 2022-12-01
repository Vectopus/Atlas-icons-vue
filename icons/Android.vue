
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,8.16h0a10.5,10.5,0,0,1,10.5,10.5v1a0,0,0,0,1,0,0H1.5a0,0,0,0,1,0,0v-1A10.5,10.5,0,0,1,12,8.16Z"/><circle class="cls-2" cx="7.23" cy="14.84" r="0.95"/><circle class="cls-2" cx="16.77" cy="14.84" r="0.95"/><line class="cls-1" x1="3.41" y1="3.39" x2="6.27" y2="9.11"/><line class="cls-1" x1="20.59" y1="3.39" x2="17.73" y2="9.11"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>