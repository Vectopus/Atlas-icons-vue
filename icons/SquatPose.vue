
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="10.11" cy="3.41" r="1.91"/><path class="cls-1" d="M19.66,7.23H8.51A1.68,1.68,0,0,0,6.9,8.44L5.41,13.68a1.47,1.47,0,0,0-.07.46h0A1.68,1.68,0,0,0,7,15.82h6v.95L8.2,21.55v.95h2.87"/><line class="cls-1" x1="10.11" y1="9.14" x2="8.2" y2="15.82"/></svg>
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