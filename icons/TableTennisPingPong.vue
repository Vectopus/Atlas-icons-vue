
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.23,4.34h0A9.05,9.05,0,0,1,20,4a9.05,9.05,0,0,1-.36,12.78,9.53,9.53,0,0,1-3.84,2.36,8.82,8.82,0,0,1-7.37-.8L4.83,21.93a2,2,0,0,1-2.76-2.76l3.62-3.63a8.82,8.82,0,0,1-.8-7.37,7.54,7.54,0,0,1,.44-1.11"/><line class="cls-1" x1="4.83" y1="8.12" x2="15.88" y2="19.17"/><circle class="cls-1" cx="4.36" cy="4.36" r="2.86"/></svg>
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