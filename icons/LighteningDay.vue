
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.89,20.54h.48a3.35,3.35,0,1,0,0-6.69H14.8a6,6,0,0,0,.09-1,4.78,4.78,0,0,0-9.56,0,3.83,3.83,0,1,0,0,7.65"/><path class="cls-1" d="M16.51,14.06a4.79,4.79,0,1,0-7-5.91"/><line class="cls-1" x1="13.93" y1="0.46" x2="13.93" y2="2.37"/><line class="cls-1" x1="23.5" y1="10.02" x2="21.59" y2="10.02"/><line class="cls-1" x1="20.7" y1="3.26" x2="19.35" y2="4.61"/><line class="cls-1" x1="8.52" y1="4.61" x2="7.17" y2="3.26"/><polygon class="cls-1" points="12.02 17.67 10.11 20.54 10.11 18.63 8.2 18.63 10.11 15.76 10.11 17.67 12.02 17.67"/></svg>
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