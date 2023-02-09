
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="3.87" cy="3.89" r="2.39"/><circle class="cls-1" cx="20.13" cy="3.89" r="2.39"/><path class="cls-1" d="M6.26,12V10.59A2.39,2.39,0,0,0,3.87,8.2h0a2.39,2.39,0,0,0-2.39,2.39V16.8H8.17v6.7"/><path class="cls-1" d="M17.74,12V10.59A2.39,2.39,0,0,1,20.13,8.2h0a2.39,2.39,0,0,1,2.39,2.39V16.8H15.83v6.7"/><line class="cls-1" x1="5.3" y1="13.93" x2="18.7" y2="13.93"/><line class="cls-1" x1="12" y1="23.5" x2="12" y2="13.93"/></svg>
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