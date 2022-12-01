
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><path class="cls-1" d="M5.32,7.23c4.17-3.82,9.19-3.82,13.36,0l-1.91,2.86a11.51,11.51,0,0,0-9.54,0Z"/><line class="cls-1" x1="12" y1="6.27" x2="12" y2="9.14"/><line class="cls-1" x1="12" y1="12.95" x2="12" y2="19.64"/></svg>
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