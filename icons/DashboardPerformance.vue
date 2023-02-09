
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M7.27,16.72A6.68,6.68,0,1,1,18,9.14"/><path class="cls-2" d="M12,13.91a1.91,1.91,0,0,1,0-3.82c1.05,0,6.68,1.91,6.68,1.91S13.05,13.91,12,13.91Z"/><line class="cls-1" x1="9.14" y1="17.73" x2="14.86" y2="17.73"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linejoin:bevel;}
</style>