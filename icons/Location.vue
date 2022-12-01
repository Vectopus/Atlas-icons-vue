
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.5,10.11c0,6.61-8.5,12.28-8.5,12.28S3.5,16.72,3.5,10.11a8.5,8.5,0,0,1,17,0Z"/><path class="cls-1" d="M12,6.33a3.78,3.78,0,1,1-3.78,3.78"/></svg>
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