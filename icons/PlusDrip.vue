
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="medicine_drip" data-name="medicine drip"><polyline class="cls-1" points="4.37 23.5 4.37 1.5 20.63 1.5"/><line class="cls-1" x1="13.93" y1="23.5" x2="13.93" y2="20.63"/><line class="cls-1" x1="13.93" y1="1.5" x2="13.93" y2="5.33"/><path class="cls-1" d="M19.67,5.33v9.56a5.74,5.74,0,0,1-5.74,5.74h0A5.74,5.74,0,0,1,8.2,14.89V5.33Z"/><line class="cls-1" x1="11.07" y1="12.98" x2="16.8" y2="12.98"/><line class="cls-1" x1="13.93" y1="10.11" x2="13.93" y2="15.85"/></g></svg>
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