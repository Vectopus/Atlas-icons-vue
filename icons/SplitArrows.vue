
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,22.5l-7.13-7.13a4.77,4.77,0,0,1,0-6.74L22.5,1.5"/><polyline class="cls-1" points="15.82 1.5 22.5 1.5 22.5 8.18"/><path class="cls-1" d="M1.5,22.5l7.13-7.13a4.77,4.77,0,0,0,0-6.74L1.5,1.5"/><polyline class="cls-1" points="8.18 1.5 1.5 1.5 1.5 8.18"/></svg>
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