
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="8.2" r="6.7"/><path class="cls-1" d="M12,14.89A3.35,3.35,0,1,1,12,8.2"/><path class="cls-1" d="M12,1.5a3.35,3.35,0,1,1,0,6.7"/><path class="cls-1" d="M5.3,8.2a3.35,3.35,0,0,1,6.7,0"/><path class="cls-1" d="M18.7,8.2a3.35,3.35,0,0,1-6.7,0"/><line class="cls-1" x1="12" y1="14.89" x2="12" y2="23.5"/></svg>
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