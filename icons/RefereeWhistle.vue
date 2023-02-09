
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.52,12.93,14.87,15.8a6.7,6.7,0,1,1-6.7-6.69H11V12l3.83-1V9.11h7.65Z"/><line class="cls-1" x1="12.96" y1="0.5" x2="12.96" y2="3.37"/><line class="cls-1" x1="7.21" y1="2.88" x2="9.24" y2="4.91"/><line class="cls-1" x1="18.71" y1="2.88" x2="16.68" y2="4.91"/></svg>
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