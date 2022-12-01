
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,9.16H14.86A7.64,7.64,0,0,1,22.5,16.8v3.82a0,0,0,0,1,0,0H1.5a0,0,0,0,1,0,0V9.16A0,0,0,0,1,1.5,9.16Z"/><line class="cls-1" x1="5.32" y1="9.16" x2="5.32" y2="20.61"/><line class="cls-1" x1="12" y1="1.52" x2="12" y2="15.84"/><rect class="cls-1" x="12" y="1.52" width="4.77" height="3.82"/><polyline class="cls-1" points="10.09 23.48 10.09 20.61 13.91 20.61 13.91 23.48"/><circle class="cls-1" cx="12" cy="14.89" r="0.95"/></svg>
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