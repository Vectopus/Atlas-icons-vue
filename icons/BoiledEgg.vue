
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.64,11.16c0,4.75-3.42,7.52-7.64,7.52s-7.64-2.77-7.64-7.52S7.78,1.5,12,1.5,19.64,6.42,19.64,11.16Z"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"/><line class="cls-1" x1="7.23" y1="22.5" x2="16.77" y2="22.5"/><path class="cls-1" d="M4.36,13a30.88,30.88,0,0,0,15.28,0"/></svg>
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