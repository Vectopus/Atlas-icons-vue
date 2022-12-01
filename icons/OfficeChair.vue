
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="office_chair" data-name="office chair"><path class="cls-1" d="M10.09,1.5h3.82a3.82,3.82,0,0,1,3.82,3.82V13a0,0,0,0,1,0,0H6.27a0,0,0,0,1,0,0V5.32A3.82,3.82,0,0,1,10.09,1.5Z"/><path class="cls-1" d="M6.75,13h10.5a2.39,2.39,0,0,1,2.39,2.39v0a1.43,1.43,0,0,1-1.43,1.43H5.8a1.43,1.43,0,0,1-1.43-1.43v0A2.39,2.39,0,0,1,6.75,13Z"/><line class="cls-1" x1="12" y1="16.77" x2="12" y2="20.59"/><circle class="cls-1" cx="8.18" cy="21.55" r="0.95"/><circle class="cls-1" cx="15.82" cy="21.55" r="0.95"/><line class="cls-2" x1="8.18" y1="20.59" x2="15.82" y2="20.59"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>