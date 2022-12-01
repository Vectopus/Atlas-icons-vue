
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="15.82 11.07 12 12.02 8.18 11.07 8.18 7.25 15.82 7.25 15.82 11.07"/><line class="cls-1" x1="4.36" y1="7.25" x2="19.64" y2="7.25"/><rect class="cls-1" x="1.5" y="1.52" width="21" height="15.27"/><line class="cls-1" x1="2.45" y1="21.57" x2="11.05" y2="21.57"/><line class="cls-1" x1="13.91" y1="21.57" x2="21.55" y2="21.57"/><line class="cls-1" x1="11.05" y1="19.66" x2="11.05" y2="23.48"/></svg>
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