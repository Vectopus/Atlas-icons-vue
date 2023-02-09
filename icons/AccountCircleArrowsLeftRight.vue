
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="11" r="2"/><path class="cls-1" d="M9,18a3,3,0,0,1,3-3h0a3,3,0,0,1,3,3"/><circle class="cls-1" cx="12" cy="12" r="7"/><polyline class="cls-1" points="12 5 3 5 7 1"/><polyline class="cls-1" points="12 19 21 19 17 23"/></svg>
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