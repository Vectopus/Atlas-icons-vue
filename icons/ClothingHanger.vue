
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.76,18.68H3.24A1.74,1.74,0,0,1,1.5,16.94h0a1.76,1.76,0,0,1,1-1.59L12,11.05l9.48,4.3a1.76,1.76,0,0,1,1,1.59h0A1.74,1.74,0,0,1,20.76,18.68Z"/><path class="cls-1" d="M12,11.05v-.26a2.53,2.53,0,0,1,1.13-2,1.91,1.91,0,1,0-3-1.54"/></svg>
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