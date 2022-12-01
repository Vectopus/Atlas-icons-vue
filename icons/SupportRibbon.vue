
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="HIV"><path class="cls-1" d="M17,1.5h0a2.12,2.12,0,0,1,0,3L3,18.5l2,2,2,2L21.29,8.21A2.41,2.41,0,0,0,22,6.5h0a5,5,0,0,0-5-5Z"/><polyline class="cls-1" points="16 13.5 21 18.5 17 22.5 12 17.5"/><path class="cls-2" d="M12,9.5l-5-5a2.12,2.12,0,0,1,0-3,5,5,0,0,0-5,5,2.41,2.41,0,0,0,.71,1.71L8,13.5"/><polyline class="cls-1" points="7 1.5 8 1.5 12.02 1.5 17 1.5"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linejoin:bevel;}
</style>