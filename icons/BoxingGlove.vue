
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.23,13.91H9.14a2.88,2.88,0,0,0,2-.84,2.86,2.86,0,0,0-2-4.89H6.27a3.82,3.82,0,0,0-1.86.49"/><path class="cls-1" d="M6.27,18a6.66,6.66,0,0,1-3.82-6A3.84,3.84,0,0,1,3.57,9.3a3.93,3.93,0,0,1,.84-.63,2,2,0,0,1,0-.49V7.23A5.74,5.74,0,0,1,10.09,1.5h5.73a5.74,5.74,0,0,1,5.73,5.73V12a6.66,6.66,0,0,1-3.82,6,6.57,6.57,0,0,1-2.87.65H9.14A6.57,6.57,0,0,1,6.27,18"/><path class="cls-1" d="M12,11.05h1.91a3.82,3.82,0,0,0,3.82-3.82"/><polyline class="cls-1" points="17.73 17.73 17.73 22.5 6.27 22.5 6.27 17.73"/></svg>
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