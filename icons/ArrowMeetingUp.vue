
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,2.5v8.93a4.6,4.6,0,0,0,3.34,4.43h0a4.61,4.61,0,0,1,3.34,4.43V23.5"/><path class="cls-1" d="M12,2.5v8.93a4.6,4.6,0,0,1-3.34,4.43h0a4.61,4.61,0,0,0-3.34,4.43V23.5"/><polyline class="cls-1" points="16.77 7.27 12 2.5 7.23 7.27"/></svg>
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