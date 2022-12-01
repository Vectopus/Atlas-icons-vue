
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="7.23" width="21" height="15.27"/><circle class="cls-1" cx="18.2" cy="11.52" r="0.48"/><circle class="cls-1" cx="18.2" cy="16.3" r="0.48"/><line class="cls-1" x1="6.27" y1="7.23" x2="17.73" y2="1.5"/><line class="cls-1" x1="4.36" y1="11.05" x2="14.86" y2="11.05"/><line class="cls-1" x1="4.36" y1="14.86" x2="14.86" y2="14.86"/><line class="cls-1" x1="4.36" y1="18.68" x2="14.86" y2="18.68"/></svg>
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