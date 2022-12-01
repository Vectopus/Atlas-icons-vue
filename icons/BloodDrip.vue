
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="Blood_drip" data-name="Blood drip"><polyline class="cls-1" points="4.37 23.5 4.37 1.5 20.63 1.5"/><line class="cls-1" x1="13.93" y1="23.5" x2="13.93" y2="20.63"/><line class="cls-1" x1="13.93" y1="1.5" x2="13.93" y2="5.33"/><path class="cls-1" d="M19.67,5.33v9.56a5.74,5.74,0,0,1-5.74,5.74h0A5.74,5.74,0,0,1,8.2,14.89V5.33Z"/><path class="cls-1" d="M16.49,13.3a2.56,2.56,0,0,1-5.11,0c0-2.23,2.55-4.15,2.55-4.15S16.49,11.07,16.49,13.3Z"/></g></svg>
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