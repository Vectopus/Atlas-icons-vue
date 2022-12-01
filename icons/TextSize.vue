
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="14.86" y1="20.59" x2="14.86" y2="3.41"/><line class="cls-1" x1="12.95" y1="20.59" x2="16.77" y2="20.59"/><polyline class="cls-1" points="22.5 5.32 22.5 3.41 7.23 3.41 7.23 5.32"/><line class="cls-1" x1="6.27" y1="20.59" x2="6.27" y2="9.14"/><line class="cls-1" x1="4.36" y1="20.59" x2="8.18" y2="20.59"/><polyline class="cls-1" points="11.04 11.04 11.04 9.14 1.5 9.14 1.5 11.04"/></svg>
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