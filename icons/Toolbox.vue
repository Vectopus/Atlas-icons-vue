
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.14" width="21" height="13.36"/><path class="cls-1" d="M3.89,1.5h0A2.39,2.39,0,0,1,6.27,3.89V9.14a0,0,0,0,1,0,0H1.5a0,0,0,0,1,0,0V3.89A2.39,2.39,0,0,1,3.89,1.5Z"/><path class="cls-1" d="M20.11,1.5h0A2.39,2.39,0,0,1,22.5,3.89V9.14a0,0,0,0,1,0,0H17.73a0,0,0,0,1,0,0V3.89A2.39,2.39,0,0,1,20.11,1.5Z"/><line class="cls-1" x1="4.36" y1="5.32" x2="19.64" y2="5.32"/><rect class="cls-1" x="8.18" y="12.95" width="7.64" height="3.82" rx="1.91"/></svg>
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