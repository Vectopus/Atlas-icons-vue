
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,22.5H9.14a8.37,8.37,0,0,1-1.91-5.73c0-3.82,2.86-6.68,2.86-8.59V3.41A1.91,1.91,0,0,1,12,1.5h0a1.91,1.91,0,0,1,1.91,1.91V8.18c0,1.91,2.86,4.77,2.86,8.59a8.37,8.37,0,0,1-1.91,5.73H12"/><line class="cls-1" x1="10.09" y1="6.27" x2="13.91" y2="6.27"/><line class="cls-1" x1="7.23" y1="18.68" x2="16.77" y2="18.68"/><line class="cls-1" x1="8.18" y1="12.95" x2="15.82" y2="12.95"/></svg>
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