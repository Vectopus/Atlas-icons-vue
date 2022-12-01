
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="14.86" cy="9.14" r="7.64"/><line class="cls-1" x1="1.5" y1="22.5" x2="9.14" y2="14.86"/><line class="cls-1" x1="14.86" y1="4.36" x2="14.86" y2="12"/><line class="cls-1" x1="12.95" y1="12.95" x2="14.86" y2="12"/><line class="cls-1" x1="16.77" y1="12.95" x2="14.86" y2="12"/><line class="cls-1" x1="14.86" y1="7.23" x2="11.05" y2="9.14"/><line class="cls-1" x1="14.86" y1="7.23" x2="18.68" y2="9.14"/></svg>
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