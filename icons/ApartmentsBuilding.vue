
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="21"/><line class="cls-1" x1="8.18" y1="5.32" x2="10.09" y2="5.32"/><line class="cls-1" x1="8.18" y1="9.14" x2="10.09" y2="9.14"/><line class="cls-1" x1="8.18" y1="12.95" x2="10.09" y2="12.95"/><line class="cls-1" x1="11.05" y1="5.32" x2="12.95" y2="5.32"/><line class="cls-1" x1="11.05" y1="9.14" x2="12.95" y2="9.14"/><line class="cls-1" x1="11.05" y1="12.95" x2="12.95" y2="12.95"/><line class="cls-1" x1="13.91" y1="5.32" x2="15.82" y2="5.32"/><line class="cls-1" x1="13.91" y1="9.14" x2="15.82" y2="9.14"/><line class="cls-1" x1="13.91" y1="12.95" x2="15.82" y2="12.95"/><rect class="cls-1" x="9.14" y="17.73" width="5.73" height="4.77"/><polygon class="cls-1" points="5.32 22.5 1.5 22.5 1.5 13.91 5.32 12 5.32 22.5"/><polygon class="cls-1" points="18.68 22.5 22.5 22.5 22.5 13.91 18.68 12 18.68 22.5"/></svg>
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