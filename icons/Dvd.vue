
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M14.86,12a2.85,2.85,0,1,1-.38-1.43A2.86,2.86,0,0,1,14.86,12Z"/><path class="cls-1" d="M12,18.68A6.69,6.69,0,0,1,5.32,12"/><path class="cls-1" d="M12,5.32A6.69,6.69,0,0,1,18.68,12"/></svg>
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