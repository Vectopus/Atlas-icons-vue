
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="5.38 6.31 9.19 2.5 13 6.31"/><path class="cls-1" d="M14.9,11.07a5.72,5.72,0,1,1-5.71,5.72V2.91"/><path class="cls-1" d="M14.9,11.07a5.68,5.68,0,0,0-3,.84"/></svg>
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