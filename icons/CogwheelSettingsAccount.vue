
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="10.09" r="1.91"/><path class="cls-1" d="M9.14,16.77A2.86,2.86,0,0,1,12,13.91h0a2.86,2.86,0,0,1,2.86,2.86"/><path class="cls-1" d="M22.5,13.91V10.09H20.37a8.55,8.55,0,0,0-1.1-2.66l1.5-1.5-2.7-2.7-1.5,1.5a8.55,8.55,0,0,0-2.66-1.1V1.5H10.09V3.63a8.55,8.55,0,0,0-2.66,1.1l-1.5-1.5-2.7,2.7,1.5,1.5a8.55,8.55,0,0,0-1.1,2.66H1.5v3.82H3.63a8.55,8.55,0,0,0,1.1,2.66l-1.5,1.5,2.7,2.7,1.5-1.5a8.55,8.55,0,0,0,2.66,1.1V22.5h3.82V20.37a8.55,8.55,0,0,0,2.66-1.1l1.5,1.5,2.7-2.7-1.5-1.5a8.55,8.55,0,0,0,1.1-2.66Z"/></svg>
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