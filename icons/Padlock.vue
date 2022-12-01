
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="11.05" width="19.09" height="11.45"/><path class="cls-1" d="M12,1.5h0a6.68,6.68,0,0,1,6.68,6.68V11a0,0,0,0,1,0,0H5.32a0,0,0,0,1,0,0V8.18A6.68,6.68,0,0,1,12,1.5Z"/><circle class="cls-1" cx="12" cy="15.82" r="0.95"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="16.77"/></svg>
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