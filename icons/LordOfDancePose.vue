
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.24,22.5H5.33V12.93h.72A9.83,9.83,0,0,0,13,10.07h0L11.07,8.15h0a6.53,6.53,0,0,1-4.62,1.92H5.33L2.46,6.24v-1L8.2,2.41V.5"/><polyline class="cls-1" points="12.98 10.06 13.94 11.02 22.54 11.02"/><line class="cls-1" x1="11.07" y1="8.15" x2="7.24" y2="4.33"/><circle class="cls-1" cx="13.93" cy="5.28" r="1.91"/></svg>
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