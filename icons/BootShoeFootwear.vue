
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.91,10.09V1.5H3.41V18.68H20.59V16.77a6.68,6.68,0,0,0-6.68-6.68Z"/><rect class="cls-1" x="3.41" y="18.68" width="17.18" height="3.82"/><path class="cls-1" d="M3.41,12h0a6.68,6.68,0,0,1,6.68,6.68v0a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V12A0,0,0,0,1,3.41,12Z"/></svg>
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