
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,1.5h0a2.67,2.67,0,0,0-1.69.61l-5,4.16V22.5H18.68V6.27l-5-4.16A2.67,2.67,0,0,0,12,1.5Z"/><circle class="cls-2" cx="12" cy="5.32" r="0.95"/><path class="cls-1" d="M9.14,12H11a3.29,3.29,0,0,1,3.29,3.29V17.2a0,0,0,0,1,0,0H12.42a3.29,3.29,0,0,1-3.29-3.29V12A0,0,0,0,1,9.14,12Z"/><line class="cls-1" x1="15.82" y1="18.68" x2="13.91" y2="16.77"/></svg>
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