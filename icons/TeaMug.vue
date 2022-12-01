
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.69,4.5h15a0,0,0,0,1,0,0V16.69a2.81,2.81,0,0,1-2.81,2.81H4.5a2.81,2.81,0,0,1-2.81-2.81V4.5a0,0,0,0,1,0,0Z"/><rect class="cls-1" x="16.69" y="7.31" width="5.62" height="8.44" rx="2.81"/><polygon class="cls-1" points="12.94 13.88 9.19 13.88 9.19 10.13 11.06 9.19 12.94 10.13 12.94 13.88"/><line class="cls-1" x1="11.06" y1="4.5" x2="11.06" y2="9.19"/></svg>
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