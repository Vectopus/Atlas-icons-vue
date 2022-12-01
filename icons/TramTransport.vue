
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,2A16.49,16.49,0,0,0,5.84,3.3,1.82,1.82,0,0,0,4.72,5V16.61a1.81,1.81,0,0,0,1.82,1.82h11a1.82,1.82,0,0,0,1.83-1.82V5A1.82,1.82,0,0,0,18.2,3.3,16.49,16.49,0,0,0,12,2Z"/><rect class="cls-1" x="4.72" y="7.48" width="14.61" height="5.48"/><circle class="cls-2" cx="7.46" cy="15.7" r="0.91"/><circle class="cls-2" cx="16.59" cy="15.7" r="0.91"/><line class="cls-1" x1="10.2" y1="4.74" x2="13.85" y2="4.74"/><line class="cls-1" x1="7.91" y1="18.43" x2="4.72" y2="23"/><line class="cls-1" x1="16.59" y1="18.43" x2="19.78" y2="23"/><line class="cls-1" x1="18.41" y1="21.17" x2="6.54" y2="21.17"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>