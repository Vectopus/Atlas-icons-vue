
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,.5V4.33h0A9.15,9.15,0,0,0,6.6,14.39l.19,1A9.32,9.32,0,0,1,6.47,20L5.29,23.5"/><path class="cls-1" d="M12,4.33a9.15,9.15,0,0,1,5.4,10.06l-.19,1A9.32,9.32,0,0,0,17.53,20l1.18,3.52"/></svg>
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