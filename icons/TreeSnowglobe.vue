
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="18.68" width="17.18" height="3.82"/><path class="cls-1" d="M12,1.5h0a7.64,7.64,0,0,1,7.64,7.64v9.55a0,0,0,0,1,0,0H4.36a0,0,0,0,1,0,0V9.14A7.64,7.64,0,0,1,12,1.5Z"/><line class="cls-1" x1="12" y1="14.86" x2="12" y2="18.68"/><polygon class="cls-1" points="14.86 14.86 9.14 14.86 12 8.18 14.86 14.86"/><line class="cls-1" x1="9.14" y1="5.32" x2="11.05" y2="5.32"/><line class="cls-1" x1="14.86" y1="6.27" x2="16.77" y2="6.27"/><line class="cls-1" x1="6.27" y1="10.09" x2="8.18" y2="10.09"/><line class="cls-1" x1="15.82" y1="11.05" x2="17.73" y2="11.05"/></svg>
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