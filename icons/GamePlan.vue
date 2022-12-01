
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="strategy"><circle class="cls-1" cx="19.16" cy="3.89" r="2.39"/><line class="cls-1" x1="2.45" y1="7.23" x2="6.27" y2="11.05"/><line class="cls-1" x1="6.27" y1="7.23" x2="2.45" y2="11.05"/><line class="cls-1" x1="17.73" y1="15.82" x2="21.55" y2="19.64"/><line class="cls-1" x1="21.55" y1="15.82" x2="17.73" y2="19.64"/><path class="cls-2" d="M15.07,8.18l-4.74,4.74a4.78,4.78,0,0,0,0,6.75l2.83,2.83"/><polyline class="cls-1" points="12 8.18 14.86 8.18 14.86 11.04"/></g></svg>
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