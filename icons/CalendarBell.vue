
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="2.43" width="21" height="4.77"/><rect class="cls-1" x="1.5" y="7.2" width="21" height="15.27"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="4.34"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="4.34"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="4.34"/><path class="cls-1" d="M12,11h0a2.86,2.86,0,0,1,2.86,2.86v2.86a0,0,0,0,1,0,0H9.14a0,0,0,0,1,0,0V13.89A2.86,2.86,0,0,1,12,11Z"/><line class="cls-1" x1="16.77" y1="16.75" x2="7.23" y2="16.75"/><circle class="cls-1" cx="12" cy="17.7" r="0.95"/></svg>
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