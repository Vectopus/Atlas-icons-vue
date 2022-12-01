
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,12h5.73a0,0,0,0,1,0,0v2.86A1.91,1.91,0,0,1,13,16.77H11a1.91,1.91,0,0,1-1.91-1.91V12a0,0,0,0,1,0,0Z"/><polyline class="cls-1" points="13.91 8.18 13.91 11.99 10.09 11.99 10.09 8.18"/><path class="cls-1" d="M12,16.77v3.61a1.88,1.88,0,0,0,2.25,1.87,10.49,10.49,0,1,0-9.68-2.83"/></svg>
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