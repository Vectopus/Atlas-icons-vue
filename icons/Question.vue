
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21"/><path class="cls-1" d="M12,13.91v-.25a2.54,2.54,0,0,1,1.13-2,1.91,1.91,0,1,0-3-1.54"/><line class="cls-1" x1="12" y1="14.86" x2="12" y2="16.77"/><circle class="cls-1" cx="12" cy="12" r="6.68"/></svg>
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