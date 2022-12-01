
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><circle class="cls-1" cx="11.99" cy="12.01" r="6.71"/><path class="cls-1" d="M12,8.65a3.36,3.36,0,0,1,0,6.72Z"/><line class="cls-1" x1="11.99" y1="0.5" x2="11.99" y2="2.42"/><line class="cls-1" x1="11.99" y1="21.6" x2="11.99" y2="23.52"/><line class="cls-1" x1="0.48" y1="12.01" x2="2.4" y2="12.01"/><line class="cls-1" x1="21.58" y1="12.01" x2="23.5" y2="12.01"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.77" y2="5.23"/><line class="cls-1" x1="5.21" y1="18.79" x2="3.85" y2="20.15"/><line class="cls-1" x1="3.85" y1="3.87" x2="5.21" y2="5.23"/><line class="cls-1" x1="18.77" y1="18.79" x2="20.13" y2="20.15"/></g></svg>
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