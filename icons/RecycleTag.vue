
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,1.5h0a2.67,2.67,0,0,0-1.69.61l-5,4.16V22.5H18.68V6.27l-5-4.16A2.67,2.67,0,0,0,12,1.5Z"/><circle class="cls-2" cx="12" cy="5.32" r="0.95"/><polyline class="cls-1" points="11.04 16.77 8.18 16.77 9.57 14.7"/><polyline class="cls-1" points="14.43 14.7 15.82 16.77 12.96 16.77"/><polyline class="cls-1" points="10.62 13.12 12 11.04 13.38 13.12"/></svg>
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