
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="eauro_coin" data-name="eauro coin"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M15.82,14.86h0A2.86,2.86,0,0,1,13,17.73H12a2.86,2.86,0,0,1-2.86-2.87V9.14A2.86,2.86,0,0,1,12,6.27H13a2.86,2.86,0,0,1,2.87,2.87h0"/><line class="cls-1" x1="7.23" y1="10.09" x2="11.05" y2="10.09"/><line class="cls-1" x1="7.23" y1="13.91" x2="11.05" y2="13.91"/></g></svg>
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