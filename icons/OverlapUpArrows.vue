
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="2.46 8.18 2.46 1.5 9.14 1.5"/><polyline class="cls-1" points="14.86 1.5 21.55 1.5 21.55 8.18"/><path class="cls-1" d="M2.45,1.5,15.39,14.43a4.76,4.76,0,0,1,1.38,3.35h0a4.72,4.72,0,0,1-4.72,4.72H12a4.72,4.72,0,0,1-4.72-4.72h0a4.76,4.76,0,0,1,1.38-3.35L21.55,1.5"/></svg>
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