
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="19" r="2"/><path class="cls-1" d="M7.29,14.06a6.66,6.66,0,0,1,9.42,0"/><path class="cls-1" d="M4.14,10.92a11.12,11.12,0,0,1,15.72,0"/><path class="cls-1" d="M1,7.78a15.55,15.55,0,0,1,22,0"/></svg>
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