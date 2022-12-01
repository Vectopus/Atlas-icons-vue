
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="1.5 0.5 1.5 22.5 23.5 22.5"/><line class="cls-1" x1="18.72" y1="10.07" x2="18.72" y2="19.63"/><line class="cls-1" x1="12.98" y1="2.41" x2="12.98" y2="19.63"/><line class="cls-1" x1="7.24" y1="6.24" x2="7.24" y2="19.63"/></svg>
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