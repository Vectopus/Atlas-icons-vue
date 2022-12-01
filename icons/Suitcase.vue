
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.14" width="21" height="11.45" rx="2.86"/><line class="cls-1" x1="6.27" y1="20.59" x2="6.27" y2="12"/><line class="cls-1" x1="17.73" y1="20.59" x2="17.73" y2="12"/><path class="cls-1" d="M11,3.41H13a3.82,3.82,0,0,1,3.82,3.82V9.14a0,0,0,0,1,0,0H7.23a0,0,0,0,1,0,0V7.23A3.82,3.82,0,0,1,11,3.41Z"/></svg>
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