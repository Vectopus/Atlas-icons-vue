
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12.02" cy="6.28" r="4.78"/><line class="cls-1" x1="7.24" y1="5.33" x2="20.63" y2="5.33"/><path class="cls-1" d="M4.37,23.5l.7-7.66A3.14,3.14,0,0,1,8.2,13h7.65A3.15,3.15,0,0,1,19,15.84l.69,7.66"/><line class="cls-1" x1="12.02" y1="12.98" x2="12.02" y2="23.5"/><line class="cls-1" x1="8.2" y1="12.98" x2="8.2" y2="23.5"/><line class="cls-1" x1="15.85" y1="12.98" x2="15.85" y2="23.5"/></svg>
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