
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="Stetoscope"><circle class="cls-1" cx="19.64" cy="19.64" r="2.86"/><path class="cls-1" d="M8.18,1.5h2.87V8.18A4.77,4.77,0,0,1,6.27,13h0A4.77,4.77,0,0,1,1.5,8.18V1.5H4.36"/><path class="cls-1" d="M6.27,13v5.73a3.82,3.82,0,0,0,3.82,3.82h0a3.82,3.82,0,0,0,3.82-3.82V13a2.86,2.86,0,0,1,2.86-2.86h0A2.87,2.87,0,0,1,19.64,13v3.82"/></g></svg>
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