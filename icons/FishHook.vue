
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><path class="cls-1" d="M12,5.32v.21a8.5,8.5,0,0,0,3.49,6.7,5.73,5.73,0,1,1-9.22,4.54"/><polyline class="cls-1" points="9.14 16.77 6.27 13.91 6.27 16.77"/></svg>
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