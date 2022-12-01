
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="digital_thermometer" data-name="digital thermometer"><path class="cls-1" d="M13.28,3.08,4.36,12v4.77L2.09,19a2,2,0,0,0-.59,1.44h0a2,2,0,0,0,2,2h0A2,2,0,0,0,5,21.91l2.27-2.27H12l8.92-8.92A5.41,5.41,0,0,0,22.5,6.9h0a5.4,5.4,0,0,0-5.4-5.4h0A5.41,5.41,0,0,0,13.28,3.08Z"/><rect class="cls-1" x="9.99" y="8.63" width="4.05" height="6.72" transform="translate(12 -4.98) rotate(45)"/><line class="cls-2" x1="15.82" y1="5.32" x2="18.68" y2="8.18"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>