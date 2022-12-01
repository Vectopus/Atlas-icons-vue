
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="8.18 6.29 12 2.48 15.82 6.29"/><rect class="cls-1" x="1.5" y="9.16" width="21" height="13.36" rx="1.91"/><line class="cls-1" x1="8.18" y1="18.7" x2="15.82" y2="18.7"/><line class="cls-1" x1="5.32" y1="15.84" x2="7.23" y2="15.84"/><line class="cls-1" x1="9.14" y1="15.84" x2="11.05" y2="15.84"/><line class="cls-1" x1="12.95" y1="15.84" x2="14.86" y2="15.84"/><line class="cls-1" x1="16.77" y1="15.84" x2="18.68" y2="15.84"/><line class="cls-1" x1="5.32" y1="12.98" x2="7.23" y2="12.98"/><line class="cls-1" x1="9.14" y1="12.98" x2="11.05" y2="12.98"/><line class="cls-1" x1="12.95" y1="12.98" x2="14.86" y2="12.98"/><line class="cls-1" x1="16.77" y1="12.98" x2="18.68" y2="12.98"/></svg>
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