
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="7.25" cy="4.36" r="2.86"/><path class="cls-1" d="M18.7,22.5H16.8V13H15.72l-4.46,7.94A3.17,3.17,0,0,1,8.5,22.5h0a3.17,3.17,0,0,1-3.16-3.16V12a1.92,1.92,0,0,1,1.91-1.91H20.61"/><line class="cls-1" x1="10.11" y1="22.05" x2="10.11" y2="12.95"/></svg>
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