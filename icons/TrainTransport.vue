
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.17,1.5h7.65a3.83,3.83,0,0,1,3.83,3.83v9.57a1.91,1.91,0,0,1-1.91,1.91H6.26a1.91,1.91,0,0,1-1.91-1.91V5.33A3.83,3.83,0,0,1,8.17,1.5Z"/><line class="cls-1" x1="8.17" y1="16.8" x2="5.3" y2="23.5"/><line class="cls-1" x1="15.83" y1="16.8" x2="18.7" y2="23.5"/><line class="cls-1" x1="6.26" y1="20.63" x2="17.74" y2="20.63"/><line class="cls-1" x1="19.65" y1="11.07" x2="4.35" y2="11.07"/><line class="cls-1" x1="7.22" y1="13.93" x2="9.13" y2="13.93"/><line class="cls-1" x1="14.87" y1="13.93" x2="16.78" y2="13.93"/></svg>
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