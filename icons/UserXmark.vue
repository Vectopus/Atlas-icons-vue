
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="9.61" cy="5.8" r="4.3"/><path class="cls-1" d="M1.5,19.64l.7-3.47a7.56,7.56,0,0,1,7.41-6.08,7.48,7.48,0,0,1,4.6,1.57"/><circle class="cls-1" cx="16.77" cy="16.77" r="5.73"/><line class="cls-1" x1="14.39" y1="14.39" x2="19.16" y2="19.16"/><line class="cls-1" x1="19.16" y1="14.39" x2="14.39" y2="19.16"/></svg>
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