
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.12,22.31l-5-5a2,2,0,0,1-.58-1.41,2,2,0,0,1,.58-1.4,2,2,0,0,1,1.41-.59,2,2,0,0,1,1.4.59l1.3,1.29V6.48a1.94,1.94,0,0,1,1.71-2,1.89,1.89,0,0,1,2,1.86V12l5,.71a1.87,1.87,0,0,1,1.61,1.85h0a16.9,16.9,0,0,1-1.79,7.58l-.09.17"/><path class="cls-1" d="M12.94,10.67a4.55,4.55,0,0,0,1.44-1,4.69,4.69,0,1,0-6.64,0,4.59,4.59,0,0,0,1.45,1"/></svg>
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