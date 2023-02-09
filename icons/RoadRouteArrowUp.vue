
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="8.18 6.32 12 2.5 15.82 6.32"/><path class="cls-1" d="M12,2.5V8.23a1.91,1.91,0,0,1-1.91,1.91H6.75a2.38,2.38,0,0,0-2.39,2.38h0a2.39,2.39,0,0,0,2.39,2.39h10.5a2.39,2.39,0,0,1,2.39,2.39h0a2.39,2.39,0,0,1-2.39,2.38H13.91A1.91,1.91,0,0,0,12,21.59V23.5"/></svg>
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