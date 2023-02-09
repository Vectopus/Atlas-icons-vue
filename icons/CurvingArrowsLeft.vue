
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="13.91 22.5 8.18 22.5 8.18 16.77"/><polyline class="cls-1" points="8.18 7.23 8.18 1.5 13.91 1.5"/><path class="cls-1" d="M8.18,22.5l5.61-5.61a6.92,6.92,0,0,0,2-4.89h0a6.92,6.92,0,0,0-2-4.89L8.18,1.5"/></svg>
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