
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="16.77" y1="12.95" x2="16.77" y2="17.73"/><line class="cls-1" x1="16.77" y1="18.68" x2="16.77" y2="20.59"/><circle class="cls-1" cx="16.77" cy="16.77" r="5.73"/><polyline class="cls-1" points="9.14 20.59 1.5 20.59 1.5 1.5 16.77 1.5 16.77 9.14"/><line class="cls-1" x1="4.36" y1="5.32" x2="13.91" y2="5.32"/><line class="cls-1" x1="4.36" y1="9.14" x2="13.91" y2="9.14"/><line class="cls-1" x1="4.36" y1="12.95" x2="9.14" y2="12.95"/><line class="cls-1" x1="4.36" y1="16.77" x2="9.14" y2="16.77"/></svg>
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