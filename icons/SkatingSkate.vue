
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="3.39" cy="20.59" r="1.91"/><circle class="cls-1" cx="9.11" cy="20.59" r="1.91"/><circle class="cls-1" cx="14.84" cy="20.59" r="1.91"/><circle class="cls-1" cx="20.57" cy="20.59" r="1.91"/><path class="cls-1" d="M.52,18.68H20.57a1.91,1.91,0,0,0,1.91-1.91V15.71a3.82,3.82,0,0,0-2.61-3.63l-4.68-1.55a1.91,1.91,0,0,1-1.3-1.82V2.85A1.35,1.35,0,0,0,12.54,1.5h0a1.35,1.35,0,0,0-1,.4L10.07,3.41H2.43V18.68"/><line class="cls-1" x1="11.02" y1="7.23" x2="13.89" y2="7.23"/><line class="cls-1" x1="12.93" y1="12" x2="14.84" y2="10.09"/><line class="cls-1" x1="18.29" y1="11.56" x2="17.7" y2="13.91"/><path class="cls-1" d="M2.43,13h1a4.77,4.77,0,0,1,4.77,4.77v1a0,0,0,0,1,0,0H2.43a0,0,0,0,1,0,0V13A0,0,0,0,1,2.43,13Z"/></svg>
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