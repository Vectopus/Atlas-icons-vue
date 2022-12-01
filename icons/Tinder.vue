
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,2.16S20,5.74,20,12.89s-4.47,9-8.95,9a8,8,0,0,1-8-8A9.68,9.68,0,0,1,6.58,6.63a5.91,5.91,0,0,0,1.79,3.58A8,8,0,0,0,12,2.16Z"/></svg>
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