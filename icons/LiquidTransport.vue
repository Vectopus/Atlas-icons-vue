
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.27" cy="17.73" r="1.91"/><circle class="cls-1" cx="17.73" cy="17.73" r="1.91"/><path class="cls-1" d="M19.64,17.73H22.5V12L21,5.81A1.9,1.9,0,0,0,19.1,4.36H15.82V17.73"/><polyline class="cls-1" points="8.18 17.73 15.82 17.73 15.82 12.96 1.5 12.96 1.5 17.73 4.36 17.73"/><rect class="cls-1" x="1.5" y="4.36" width="14.32" height="8.59" rx="4.3"/><polyline class="cls-1" points="15.82 10.09 17.73 10.09 19.64 12 22.5 12"/><line class="cls-1" x1="6.27" y1="7.23" x2="6.27" y2="12.95"/><line class="cls-1" x1="11.05" y1="7.23" x2="11.05" y2="12.95"/></svg>
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