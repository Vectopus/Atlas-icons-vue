
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="3.41" width="21" height="17.18"/><circle class="cls-1" cx="7.7" cy="11.52" r="2.39"/><circle class="cls-1" cx="16.3" cy="11.52" r="2.39"/><line class="cls-1" x1="7.7" y1="13.91" x2="16.3" y2="13.91"/></svg>
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