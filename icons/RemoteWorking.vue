
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M3.39,22.5H1.48V19.64a2.86,2.86,0,0,1,4.88-2,2.18,2.18,0,0,1,.42.54"/><circle class="cls-1" cx="4.34" cy="12.95" r="1.91"/><polygon class="cls-1" points="13.89 22.5 8.16 22.5 9.11 17.73 14.84 17.73 13.89 22.5"/><line class="cls-1" x1="9.11" y1="22.5" x2="4.34" y2="22.5"/><circle class="cls-1" cx="15.8" cy="7.23" r="5.73"/><ellipse class="cls-1" cx="15.8" cy="7.23" rx="1.91" ry="5.73"/><line class="cls-1" x1="10.07" y1="7.23" x2="21.52" y2="7.23"/></svg>
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