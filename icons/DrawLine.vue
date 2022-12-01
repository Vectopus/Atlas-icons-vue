
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.24,22.52,2.09,17.38a2,2,0,0,1,1.44-3.47,2,2,0,0,1,1.43.6l1.32,1.32V6.37A2,2,0,0,1,8,4.36a1.83,1.83,0,0,1,1.51.55,1.86,1.86,0,0,1,.57,1.35V12l5.05.72a1.92,1.92,0,0,1,1.64,1.9h0A17.22,17.22,0,0,1,15,22.34l-.09.18"/><polyline class="cls-1" points="10.11 6.26 19.67 6.26 13.94 1.48 23.5 1.48"/></svg>
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