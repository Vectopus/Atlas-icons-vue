
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.64,5.32,21.55,1.5H2.45L4.36,5.32a17,17,0,0,0,0,13.36L2.45,22.5h19.1l-1.91-3.82A17,17,0,0,0,19.64,5.32Z"/><line class="cls-1" x1="15.82" y1="5.32" x2="4.36" y2="5.32"/><line class="cls-1" x1="15.82" y1="18.68" x2="4.36" y2="18.68"/><polygon class="cls-1" points="12.02 10.09 9.17 14.86 14.86 14.86 12.02 10.09"/></svg>
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