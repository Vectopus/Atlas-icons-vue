
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.73,17.72h2.86a1.92,1.92,0,0,0,1.91-1.91V3.4a1.91,1.91,0,0,0-1.91-1.9H3.41A1.91,1.91,0,0,0,1.5,3.4V15.81a1.92,1.92,0,0,0,1.91,1.91H6.27"/><rect class="cls-1" x="1.5" y="5.31" width="21" height="3.82"/><path class="cls-1" d="M12,22.3h0a5.24,5.24,0,0,1-3.78-5v-3L12,13.14l3.86,1.1v3A5.3,5.3,0,0,1,12,22.3Z"/></svg>
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