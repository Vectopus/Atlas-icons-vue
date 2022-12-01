
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.42" y="2.42" width="19.17" height="19.17"/><path class="cls-1" d="M12,13h0a3.83,3.83,0,0,1,3.83,3.83v4.79a0,0,0,0,1,0,0H8.17a0,0,0,0,1,0,0V16.79A3.83,3.83,0,0,1,12,13Z"/><line class="cls-1" x1="0.5" y1="8.17" x2="23.5" y2="8.17"/><line class="cls-1" x1="0.5" y1="21.58" x2="23.5" y2="21.58"/><line class="cls-1" x1="6.25" y1="5.29" x2="6.25" y2="8.17"/><line class="cls-1" x1="10.08" y1="5.29" x2="10.08" y2="8.17"/><line class="cls-1" x1="13.92" y1="5.29" x2="13.92" y2="8.17"/><line class="cls-1" x1="17.75" y1="5.29" x2="17.75" y2="8.17"/><line class="cls-1" x1="18.71" y1="12.96" x2="18.71" y2="15.83"/><line class="cls-1" x1="5.29" y1="12.96" x2="5.29" y2="15.83"/></svg>
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