
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="3.82"/><path class="cls-1" d="M8.18,14.86V22.5H2.45V5.32h19.1V22.5H15.82V14.86A3.81,3.81,0,0,0,12,11.05h0A3.81,3.81,0,0,0,8.18,14.86Z"/><line class="cls-1" x1="0.55" y1="5.32" x2="23.45" y2="5.32"/><line class="cls-1" x1="0.55" y1="11.05" x2="23.45" y2="11.05"/><circle class="cls-2" cx="6.27" cy="8.18" r="0.95"/><circle class="cls-2" cx="10.09" cy="8.18" r="0.95"/><circle class="cls-2" cx="17.73" cy="8.18" r="0.95"/><circle class="cls-2" cx="13.91" cy="8.18" r="0.95"/><line class="cls-1" x1="5.32" y1="18.68" x2="5.32" y2="22.5"/><line class="cls-1" x1="18.68" y1="18.68" x2="18.68" y2="22.5"/><line class="cls-1" x1="0.55" y1="14.86" x2="8.18" y2="14.86"/><line class="cls-1" x1="15.12" y1="14.86" x2="23.45" y2="14.86"/><line class="cls-1" x1="1.5" y1="1.5" x2="22.5" y2="1.5"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>