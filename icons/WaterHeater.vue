
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.29" y="1.46" width="13.42" height="17.25"/><line class="cls-1" x1="5.29" y1="14.87" x2="18.71" y2="14.87"/><path class="cls-1" d="M13.92,9.13a1.92,1.92,0,0,1-3.84,0C10.08,7.21,12,5.29,12,5.29S13.92,7.21,13.92,9.13Z"/><path class="cls-1" d="M9.13,18.71v1.91a1.92,1.92,0,0,1-1.92,1.92H.5"/><path class="cls-1" d="M14.87,18.71v1.91a1.93,1.93,0,0,0,1.92,1.92H23.5"/></svg>
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