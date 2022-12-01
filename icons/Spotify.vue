
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M5.8,9.28a11,11,0,0,1,12.4,0"/><path class="cls-1" d="M6.75,13.06a10.34,10.34,0,0,1,10.5,0"/><path class="cls-1" d="M7.7,16.84a10.11,10.11,0,0,1,8.6,0"/></svg>
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