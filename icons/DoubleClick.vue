
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11.37,12.73,7.44,8.8a1.86,1.86,0,0,0-2.73.12,1.93,1.93,0,0,0,.19,2.57l5.82,5.82H8.91a2,2,0,0,0-1.39.58A2,2,0,0,0,7,19.27a2,2,0,0,0,2,2h7"/><path class="cls-1" d="M11.37,12.73,7.44,8.8l-.58-.58a1.93,1.93,0,0,1-.35-2.33,1.86,1.86,0,0,1,2.9-.36l4.3,4.3,2.33-2A1.74,1.74,0,0,1,18.4,8h0a16.84,16.84,0,0,1,4,6.54l.06.18"/><path class="cls-1" d="M7.82,14.42a4.42,4.42,0,0,1-1.69.32A4.62,4.62,0,0,1,3.5,6.31a4.63,4.63,0,0,1,9.23.53,4.41,4.41,0,0,1-.32,1.68"/></svg>
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