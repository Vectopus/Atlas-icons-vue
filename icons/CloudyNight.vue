
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.35,15.83h-.57a5,5,0,0,0,.09-.95,4.79,4.79,0,1,0-9.58,0,3.83,3.83,0,1,0,0,7.66H15.35a3.36,3.36,0,1,0,0-6.71Z"/><path class="cls-1" d="M14.87,14.8a5.11,5.11,0,0,0,1,.08,6.68,6.68,0,0,0,6.62-5.69,4.8,4.8,0,0,1-7.58-3.9A4.83,4.83,0,0,1,16.7,1.52a6.15,6.15,0,0,0-.87-.06A6.7,6.7,0,0,0,9.12,8.17a7.05,7.05,0,0,0,.29,2"/></svg>
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