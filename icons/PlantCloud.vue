
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,14.86H16.44a5.72,5.72,0,0,0-10.35-.95H5.8a4.3,4.3,0,1,0,0,8.59H18.68a3.82,3.82,0,0,0,0-7.64Z"/><path class="cls-1" d="M9.14,1.5H11a4.77,4.77,0,0,1,4.77,4.77v0a0,0,0,0,1,0,0H13.91A4.77,4.77,0,0,1,9.14,1.5v0A0,0,0,0,1,9.14,1.5Z"/><path class="cls-1" d="M20.59,1.5H22.5a0,0,0,0,1,0,0v0a4.77,4.77,0,0,1-4.77,4.77H15.82a0,0,0,0,1,0,0v0A4.77,4.77,0,0,1,20.59,1.5Z" transform="translate(38.32 7.77) rotate(-180)"/><line class="cls-1" x1="15.82" y1="13.91" x2="15.82" y2="6.27"/></svg>
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