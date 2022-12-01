
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="umbrella_insurance" data-name="umbrella insurance"><path class="cls-1" d="M15.82,20.59a1.93,1.93,0,0,1-1.91,1.91A1.92,1.92,0,0,1,12,20.59V13"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="3.41"/><path class="cls-1" d="M12,3.41h0A8.59,8.59,0,0,1,20.59,12v1a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V12A8.59,8.59,0,0,1,12,3.41Z"/></g></svg>
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