
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,9.14V5.55a4,4,0,0,0-4-4H5.55a4,4,0,0,0-4,4.05V18.68A3.82,3.82,0,0,0,5.32,22.5H18.68a3.82,3.82,0,0,0,3.82-3.82V13a1.9,1.9,0,0,0-1.91-1.9h0A1.92,1.92,0,0,1,18.68,9.14Z"/><rect class="cls-1" x="6.27" y="6.27" width="7.64" height="3.82" rx="1.91"/><rect class="cls-1" x="6.27" y="14.86" width="10.5" height="3.82" rx="1.91"/></svg>
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