
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13,9.14l-2.53-2a8.17,8.17,0,0,0-5.1-1.79H3.41V3.41A1.9,1.9,0,0,1,5.32,1.5h0a13.17,13.17,0,0,1,8.44,3.06l.82.68a3.45,3.45,0,0,1,1.24,2.65h0A3.45,3.45,0,0,1,15,10.1l-4,4.76V22.5"/><polyline class="cls-1" points="3.41 5.32 3.41 22.5 6.27 22.5"/><circle class="cls-1" cx="18.2" cy="13.43" r="2.39"/></svg>
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