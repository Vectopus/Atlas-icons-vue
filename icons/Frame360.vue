
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.23,8.09H5.16a2,2,0,0,1,2,2h0A2,2,0,0,1,5.16,12H3.21"/><path class="cls-1" d="M2.23,15.91H5.16a2,2,0,0,0,2-2h0A2,2,0,0,0,5.16,12H3.21"/><circle class="cls-1" cx="12" cy="13.95" r="1.95"/><path class="cls-1" d="M10.05,14V12A3.91,3.91,0,0,1,14,8.09h0"/><rect class="cls-1" x="16.89" y="8.09" width="3.91" height="7.82" rx="1.95"/><polyline class="cls-1" points="1.25 5.16 1.25 1.25 5.16 1.25"/><polyline class="cls-1" points="5.16 22.75 1.25 22.75 1.25 18.84"/><polyline class="cls-1" points="22.75 18.84 22.75 22.75 18.84 22.75"/><polyline class="cls-1" points="18.84 1.25 22.75 1.25 22.75 5.16"/></svg>
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