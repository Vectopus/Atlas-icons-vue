
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.69.31a3.44,3.44,0,0,0,.68,2.07c.69.68,8.25,0,10.32,2.06s1.37,2.75,2.75,4.12"/><path class="cls-1" d="M23.69,22.31a3.44,3.44,0,0,1-2.07-.68c-.68-.69,0-8.25-2.06-10.32s-2.75-1.37-4.12-2.75"/><line class="cls-1" x1="3.75" y1="20.25" x2="14.06" y2="9.94"/><line class="cls-1" x1="22.31" y1="1.69" x2="16.81" y2="7.19"/><polyline class="cls-1" points="21.62 5.13 22.31 1.69 18.87 2.38"/><polygon class="cls-1" points="5.41 15.84 8.13 15.87 8.16 18.59 5.41 21.34 4.44 19.56 2.66 18.59 5.41 15.84"/><line class="cls-1" x1="2.37" y1="2.38" x2="4.24" y2="13.93"/><line class="cls-1" x1="21.62" y1="21.63" x2="10.07" y2="19.76"/></svg>
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