
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,1.5H18.68L8.89,11.29a5.7,5.7,0,1,0,3.82,3.82L22.5,5.32Z"/><circle class="cls-1" cx="6.27" cy="17.73" r="0.95"/><line class="cls-1" x1="14.86" y1="10.09" x2="16.3" y2="11.52"/><line class="cls-1" x1="17.73" y1="7.23" x2="18.68" y2="8.18"/></svg>
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