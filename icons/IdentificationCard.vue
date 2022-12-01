
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="id_card" data-name="id card"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/><path class="cls-1" d="M8.18,12h0A2.86,2.86,0,0,1,11,14.86v1a0,0,0,0,1,0,0H5.32a0,0,0,0,1,0,0v-1A2.86,2.86,0,0,1,8.18,12Z"/><circle class="cls-1" cx="8.18" cy="10.09" r="1.91"/><path class="cls-1" d="M19.64,8.18h0Z"/><path class="cls-1" d="M19.64,12h0Z"/><path class="cls-1" d="M19.64,15.82h0Z"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>