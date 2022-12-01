
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="bandage"><path class="cls-1" d="M13.91,2.45h0a3.25,3.25,0,0,1,2.3-1h.17a3.25,3.25,0,0,1,2.3,1l2.87,2.87a3.25,3.25,0,0,1,.95,2.3v.17a3.25,3.25,0,0,1-.95,2.3L10.09,21.55a3.25,3.25,0,0,1-2.3.95H7.62a3.25,3.25,0,0,1-2.3-.95L2.45,18.68a3.25,3.25,0,0,1-1-2.3v-.17a3.25,3.25,0,0,1,1-2.3L13,3.41Z"/><polygon class="cls-1" points="11.52 15.34 8.66 12.48 12.48 8.66 13.69 9.87 15.34 11.52 11.52 15.34"/></g></svg>
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