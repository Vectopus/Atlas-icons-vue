
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12.81,14.91h6.86V7.26H1.5V12a2.86,2.86,0,0,0,2.87,2.87h3"/><line class="cls-1" x1="23.5" y1="14.91" x2="17.76" y2="14.91"/><line class="cls-1" x1="21.59" y1="18.74" x2="21.59" y2="14.91"/><circle class="cls-1" cx="10.11" cy="15.87" r="2.87"/></svg>
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