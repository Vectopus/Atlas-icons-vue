
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1,13.55A5.89,5.89,0,1,1,3.16,21.6"/><path class="cls-1" d="M20.84,21.6a5.89,5.89,0,1,1,2.16-8"/><path class="cls-1" d="M16.17,1.61a5.9,5.9,0,1,1-8.34,0"/><circle class="cls-1" cx="12" cy="12.74" r="6.43"/></svg>
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