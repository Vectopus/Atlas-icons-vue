
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.37" cy="12.96" r="2.87"/><path class="cls-1" d="M9.15,22.52H12V14.87l-4-4.63h0A2.6,2.6,0,0,1,8.43,6.5l5.73-4.45a2.69,2.69,0,0,1,1.66-.57H16a2.7,2.7,0,0,1,2.71,2.7h0a2.72,2.72,0,0,1-.8,1.92L13,11v1H23.5"/></svg>
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