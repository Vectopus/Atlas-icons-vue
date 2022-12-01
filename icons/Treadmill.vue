
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,15.8h0a6.68,6.68,0,0,1,6.68,6.68v0a0,0,0,0,1,0,0H1.5a0,0,0,0,1,0,0V15.8A0,0,0,0,1,1.5,15.8Z"/><path class="cls-1" d="M7.23,22.48H20.59a1.93,1.93,0,0,0,1.91-1.91,1.92,1.92,0,0,0-1.91-1.91H7.23l-.24,0"/><path class="cls-1" d="M7.26,7.58l-2.9.58V3.39L9.14,5.3h0A2.33,2.33,0,0,1,7.26,7.58Z"/><line class="cls-1" x1="16.77" y1="5.3" x2="9.14" y2="5.3"/><line class="cls-1" x1="3.41" y1="0.52" x2="4.36" y2="3.39"/><line class="cls-1" x1="4.36" y1="7.2" x2="2.45" y2="15.8"/></svg>
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