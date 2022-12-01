
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.72,9.1h5a3.82,3.82,0,1,0,0-7.64H5.32a3.82,3.82,0,0,0,0,7.64H8.84"/><polygon class="cls-1" points="21.94 18.25 17.54 13.85 21.3 11.72 8.18 7.19 12.71 20.31 14.84 16.55 19.24 20.95 21.94 18.25"/></svg>
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