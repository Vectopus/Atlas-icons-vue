
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.27" cy="14.89" r="2.86"/><path class="cls-1" d="M1.5,23.48v-1a4.78,4.78,0,0,1,4.77-4.77h0a4.78,4.78,0,0,1,4.78,4.77v1"/><path class="cls-1" d="M9.14,3.43V9.16a1.91,1.91,0,0,0,1.91,1.91h2.86V13l2.86-1.91h3.82A1.91,1.91,0,0,0,22.5,9.16V3.43a1.91,1.91,0,0,0-1.91-1.91H11.05A1.91,1.91,0,0,0,9.14,3.43Z"/><line class="cls-1" x1="12" y1="6.3" x2="19.64" y2="6.3"/></svg>
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