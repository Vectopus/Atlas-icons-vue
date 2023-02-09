
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.35,20.8,8.18,22.5H3.89A2.39,2.39,0,0,1,1.5,20.11h0a2.39,2.39,0,0,1,2.39-2.38h0A5.76,5.76,0,0,1,8,19.41Z"/><polyline class="cls-1" points="8.18 22.5 9.35 20.8 22.5 1.5"/></svg>
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