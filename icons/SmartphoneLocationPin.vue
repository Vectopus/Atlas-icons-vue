
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,17.51v3.21a1.78,1.78,0,0,1-1.78,1.78H3.28A1.78,1.78,0,0,1,1.5,20.72V3.28A1.78,1.78,0,0,1,3.28,1.5h9.8a1.78,1.78,0,0,1,1.78,1.78V4.7"/><line class="cls-1" x1="7.23" y1="18.68" x2="9.14" y2="18.68"/><path class="cls-1" d="M22.5,10.09c0,3.82-5.73,9.55-5.73,9.55s-5.72-5.73-5.72-9.55a5.73,5.73,0,1,1,11.45,0Z"/><circle class="cls-1" cx="16.77" cy="10.09" r="1.91"/></svg>
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