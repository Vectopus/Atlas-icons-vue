
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><line class="cls-1" x1="5.24" y1="11.03" x2="18.66" y2="11.03"/><line class="cls-1" x1="7.16" y1="6.24" x2="16.75" y2="6.24"/><polygon class="cls-1" points="22.5 14.87 22.5 22.54 1.4 22.54 1.4 14.87 5.24 1.44 18.66 1.44 22.5 14.87"/><path class="cls-1" d="M2.36,14.87H8.11a3.84,3.84,0,0,0,7.68,0h5.75"/><path class="cls-1" d="M22.5,14.87H15.79a3.84,3.84,0,0,1-7.68,0H1.4"/></g></svg>
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