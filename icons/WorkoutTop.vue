
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,13.91V22.5H1.5V13.91h0A6.42,6.42,0,0,0,4.36,8.56V1.5H8.18V7.06a3.93,3.93,0,0,0,3.45,4,3.83,3.83,0,0,0,4.19-3.8V1.5h3.82V8.56a6.42,6.42,0,0,0,2.86,5.35Z"/><line class="cls-1" x1="8.18" y1="1.5" x2="15.82" y2="9.14"/><line class="cls-1" x1="15.82" y1="1.5" x2="8.18" y2="9.14"/><line class="cls-1" x1="1.5" y1="18.68" x2="22.5" y2="18.68"/></svg>
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