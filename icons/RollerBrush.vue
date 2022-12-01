
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="17.18" height="5.73"/><path class="cls-1" d="M5.32,4.36H4.84A3.35,3.35,0,0,0,1.5,7.7h0a3.35,3.35,0,0,0,3.34,3.35h9.07v3.81"/><path class="cls-1" d="M12,14.86h3.82a0,0,0,0,1,0,0v5.73a1.91,1.91,0,0,1-1.91,1.91h0A1.91,1.91,0,0,1,12,20.59V14.86A0,0,0,0,1,12,14.86Z"/></svg>
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