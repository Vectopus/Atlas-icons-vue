
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="2.43" width="21" height="4.77"/><rect class="cls-1" x="1.5" y="7.2" width="21" height="15.27"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="4.34"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="4.34"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="4.34"/><line class="cls-1" x1="12" y1="11.98" x2="12" y2="17.7"/><polyline class="cls-1" points="13.91 10.07 12 11.98 10.09 10.07"/><polyline class="cls-1" points="10.09 19.61 12 17.7 13.91 19.61"/><line class="cls-1" x1="14.86" y1="14.84" x2="9.14" y2="14.84"/><polyline class="cls-1" points="16.77 16.75 14.86 14.84 16.77 12.93"/><polyline class="cls-1" points="7.23 12.93 9.14 14.84 7.23 16.75"/><circle class="cls-1" cx="12" cy="14.84" r="0.95"/></svg>
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