
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.37,14.85h-.58a4.34,4.34,0,0,0,.1-1,4.78,4.78,0,0,0-9.56,0,3.83,3.83,0,1,0,0,7.65h10a3.35,3.35,0,1,0,0-6.69Z"/><path class="cls-1" d="M16.51,15.06a4.79,4.79,0,1,0-7-5.91"/><line class="cls-1" x1="13.93" y1="1.46" x2="13.93" y2="3.37"/><line class="cls-1" x1="23.5" y1="11.02" x2="21.59" y2="11.02"/><line class="cls-1" x1="20.7" y1="4.26" x2="19.35" y2="5.61"/><line class="cls-1" x1="8.52" y1="5.61" x2="7.17" y2="4.26"/></svg>
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