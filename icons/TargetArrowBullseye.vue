
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.61,8A9.49,9.49,0,1,1,16,3.39"/><path class="cls-1" d="M16.42,10.26A4.6,4.6,0,0,1,16.75,12,4.75,4.75,0,1,1,12,7.25a4.6,4.6,0,0,1,1.74.33"/><polyline class="cls-1" points="12 12 17.7 6.3 17.7 4.4 19.6 2.5 19.6 4.4 21.5 4.4 19.6 6.3 17.7 6.3"/><circle class="cls-1" cx="12" cy="12" r="0.95"/></svg>
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