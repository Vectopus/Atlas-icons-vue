
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="5.32" cy="18.7" r="3.82"/><path class="cls-1" d="M5.32,14.89H18.68A3.82,3.82,0,0,1,22.5,18.7h0a3.82,3.82,0,0,1-3.82,3.82H5.32"/><path class="cls-1" d="M16.77,10.11a4.77,4.77,0,1,1-9.54,0c0-2.83,1.68-4.37,3-5.93l.78,1.16L12,2.48S16.77,5.34,16.77,10.11Z"/><path class="cls-1" d="M13.91,12.79a1.91,1.91,0,0,1-3.82,0c0-1.91,1.91-3.44,1.91-3.44S13.91,10.88,13.91,12.79Z"/></svg>
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