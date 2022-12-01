
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.45,7.33H17A5.83,5.83,0,0,0,17,6.49,5,5,0,0,0,7,6.49a4.2,4.2,0,0,0,0,8.39H17.45a3.78,3.78,0,0,0,0-7.55Z"/><line class="cls-1" x1="21.58" y1="18.71" x2="8.17" y2="18.71"/><line class="cls-1" x1="6.25" y1="18.71" x2="0.5" y2="18.71"/><line class="cls-1" x1="23.5" y1="22.54" x2="16.79" y2="22.54"/><line class="cls-1" x1="14.88" y1="22.54" x2="3.38" y2="22.54"/></svg>
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