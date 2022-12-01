
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,1.5h0a5.73,5.73,0,0,1,5.73,5.73v6.68a1.91,1.91,0,0,1-1.91,1.91H8.18a1.91,1.91,0,0,1-1.91-1.91V7.23A5.73,5.73,0,0,1,12,1.5Z"/><line class="cls-1" x1="10.09" y1="6.27" x2="10.09" y2="12.95"/><line class="cls-1" x1="13.91" y1="6.27" x2="13.91" y2="12.95"/><path class="cls-1" d="M10.09,15.82h3.82a0,0,0,0,1,0,0v4.77A1.91,1.91,0,0,1,12,22.5h0a1.91,1.91,0,0,1-1.91-1.91V15.82a0,0,0,0,1,0,0Z"/></svg>
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