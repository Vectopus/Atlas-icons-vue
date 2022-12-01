
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="5.8" cy="5.82" r="4.3"/><circle class="cls-1" cx="18.2" cy="5.82" r="4.3"/><path class="cls-1" d="M9.4,3.5a3.82,3.82,0,0,1,5.2,0"/><line class="cls-1" x1="22.5" y1="23.48" x2="22.5" y2="6.3"/></svg>
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