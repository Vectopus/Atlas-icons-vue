
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M4.35,1.5h15.3a0,0,0,0,1,0,0v1A7.65,7.65,0,0,1,12,10.11h0A7.65,7.65,0,0,1,4.35,2.46v-1A0,0,0,0,1,4.35,1.5Z"/><line class="cls-1" x1="17.63" y1="18.73" x2="15.53" y2="9.24"/><polyline class="cls-1" points="5.3 23.5 5.3 21.59 8.4 9.2"/><line class="cls-1" x1="13.91" y1="15.85" x2="6.26" y2="15.85"/><circle class="cls-1" cx="17.74" cy="20.63" r="1.91"/></svg>
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