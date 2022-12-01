
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,13V8.28a2,2,0,0,0-1.59-2A1.9,1.9,0,0,0,12,8.18V15.5L11.46,15a2,2,0,0,0-2.53-.28,1.91,1.91,0,0,0-.25,2.91L12,20.9l1.91,1.6h6.68a6.52,6.52,0,0,0,1.91-4.61V15.82A2.87,2.87,0,0,0,19.64,13Z"/><path class="cls-1" d="M9.83,1.5a3.12,3.12,0,0,0-2.6,1.37A3.13,3.13,0,0,0,4.62,1.5,3.09,3.09,0,0,0,1.5,4.55c0,4.59,5.73,6.11,5.73,6.11S13,9.14,13,4.55A3.08,3.08,0,0,0,9.83,1.5Z"/></svg>
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