
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="bitcoin"><path class="cls-1" d="M7.23,4.36h7.64a3.82,3.82,0,0,1,3.82,3.82v0A3.82,3.82,0,0,1,14.86,12H7.23a0,0,0,0,1,0,0V4.36a0,0,0,0,1,0,0Z"/><path class="cls-1" d="M7.23,12h7.64a3.82,3.82,0,0,1,3.82,3.82v0a3.82,3.82,0,0,1-3.82,3.82H7.23a0,0,0,0,1,0,0V12a0,0,0,0,1,0,0Z"/><line class="cls-1" x1="5.32" y1="4.36" x2="7.23" y2="4.36"/><line class="cls-1" x1="5.32" y1="19.64" x2="7.23" y2="19.64"/><line class="cls-1" x1="10.09" y1="1.5" x2="10.09" y2="4.36"/><line class="cls-1" x1="13.91" y1="1.5" x2="13.91" y2="4.36"/><line class="cls-1" x1="10.09" y1="19.64" x2="10.09" y2="22.5"/><line class="cls-1" x1="13.91" y1="19.64" x2="13.91" y2="22.5"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>