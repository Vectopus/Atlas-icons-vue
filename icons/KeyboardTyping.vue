
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="5.32" width="21" height="13.36" rx="1.91"/><line class="cls-1" x1="8.18" y1="14.86" x2="15.82" y2="14.86"/><line class="cls-1" x1="5.32" y1="12" x2="7.23" y2="12"/><line class="cls-1" x1="9.14" y1="12" x2="11.05" y2="12"/><line class="cls-1" x1="12.95" y1="12" x2="14.86" y2="12"/><line class="cls-1" x1="16.77" y1="12" x2="18.68" y2="12"/><line class="cls-1" x1="5.32" y1="9.14" x2="7.23" y2="9.14"/><line class="cls-1" x1="9.14" y1="9.14" x2="11.05" y2="9.14"/><line class="cls-1" x1="12.95" y1="9.14" x2="14.86" y2="9.14"/><line class="cls-1" x1="16.77" y1="9.14" x2="18.68" y2="9.14"/></svg>
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