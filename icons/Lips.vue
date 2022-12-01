
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="lips"><path class="cls-1" d="M18.11,7.14a5.33,5.33,0,0,0-2.95-.89,5.26,5.26,0,0,0-2.37.56L12,7.2l-.79-.39a5.26,5.26,0,0,0-2.37-.56,5.33,5.33,0,0,0-2.95.89L1.5,10.07a9.21,9.21,0,0,0,8.86,6.68h3.28a9.22,9.22,0,0,0,8.86-6.68Z"/><path class="cls-1" d="M1.5,10.07h0a30.8,30.8,0,0,0,21,0h0"/></g></svg>
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