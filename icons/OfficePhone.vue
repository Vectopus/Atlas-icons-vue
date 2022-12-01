
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,4.39H20.59A1.91,1.91,0,0,1,22.5,6.3V17.75a1.91,1.91,0,0,1-1.91,1.91H9.14a0,0,0,0,1,0,0V4.39A0,0,0,0,1,9.14,4.39Z"/><rect class="cls-1" x="1.5" y="2.48" width="7.64" height="20.05" rx="1.96"/><line class="cls-1" x1="12" y1="12.02" x2="13.91" y2="12.02"/><line class="cls-1" x1="14.86" y1="12.02" x2="16.77" y2="12.02"/><line class="cls-1" x1="17.73" y1="12.02" x2="19.64" y2="12.02"/><line class="cls-1" x1="12" y1="15.84" x2="13.91" y2="15.84"/><line class="cls-1" x1="14.86" y1="15.84" x2="16.77" y2="15.84"/><line class="cls-1" x1="17.73" y1="15.84" x2="19.64" y2="15.84"/><line class="cls-1" x1="12" y1="8.2" x2="19.64" y2="8.2"/></svg>
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