
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="eauro"><path class="cls-1" d="M20.59,16.77h0a5.72,5.72,0,0,1-5.73,5.73H12a5.73,5.73,0,0,1-5.73-5.73V7.23A5.73,5.73,0,0,1,12,1.5h2.86a5.72,5.72,0,0,1,5.73,5.73h0"/><line class="cls-1" x1="3.41" y1="9.14" x2="10.09" y2="9.14"/><line class="cls-1" x1="3.41" y1="14.86" x2="10.09" y2="14.86"/></g></svg>
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