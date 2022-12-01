
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="test_tube" data-name="test tube"><path class="cls-1" d="M8.18,1.5h7.64a0,0,0,0,1,0,0V18.68A3.82,3.82,0,0,1,12,22.5h0a3.82,3.82,0,0,1-3.82-3.82V1.5A0,0,0,0,1,8.18,1.5Z"/><line class="cls-1" x1="5.32" y1="1.5" x2="18.68" y2="1.5"/><path class="cls-1" d="M8.18,8.18C12,8.18,12,6.27,15.82,6.27"/><line class="cls-1" x1="10.09" y1="12.95" x2="12" y2="12.95"/><line class="cls-1" x1="12" y1="17.73" x2="13.91" y2="17.73"/></g></svg>
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