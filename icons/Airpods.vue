
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="4.36" y1="6.27" x2="7.23" y2="6.27"/><path class="cls-1" d="M12,3.54V9a11.81,11.81,0,0,1-5.87,2.05A4.36,4.36,0,0,1,5.32,11V22.5H1.5V6.27A4.7,4.7,0,0,1,6.13,1.5,11.79,11.79,0,0,1,12,3.54Z"/><line class="cls-1" x1="19.64" y1="17.73" x2="16.77" y2="17.73"/><path class="cls-1" d="M12,20.46V15A11.81,11.81,0,0,1,17.87,13a4.36,4.36,0,0,1,.81.08V1.5H22.5V17.73a4.7,4.7,0,0,1-4.63,4.77A11.79,11.79,0,0,1,12,20.46Z"/></svg>
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