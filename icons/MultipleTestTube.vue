
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8.18" y1="1.5" x2="15.82" y2="1.5"/><line class="cls-1" x1="6.27" y1="14.86" x2="17.73" y2="14.86"/><line class="cls-1" x1="8.18" y1="18.68" x2="10.09" y2="18.68"/><line class="cls-1" x1="13.91" y1="17.73" x2="15.82" y2="17.73"/><path class="cls-1" d="M21,10.49l-2.7-2.7-3.78,3.77a6.19,6.19,0,0,0-.6-.23V1.5H10.09v9.83a6.19,6.19,0,0,0-.6.23L5.71,7.79,3,10.49,6.5,14a6.63,6.63,0,0,0,.83,8.53h9.34A6.63,6.63,0,0,0,17.5,14Z"/><line class="cls-1" x1="1.5" y1="12" x2="7.23" y2="6.27"/><line class="cls-1" x1="16.77" y1="6.27" x2="22.5" y2="12"/></svg>
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