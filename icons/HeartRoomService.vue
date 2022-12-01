
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12.87,15.6a1.06,1.06,0,0,0-.87.47,1.06,1.06,0,0,0-.87-.47,1,1,0,0,0-1,1c0,1.56,1.91,2.09,1.91,2.09s1.91-.53,1.91-2.09A1,1,0,0,0,12.87,15.6Z"/><path class="cls-2" d="M7.23,6.27a4.77,4.77,0,0,1,9.54,0"/><path class="cls-2" d="M16.77,6.27V20.59a1.9,1.9,0,0,1-1.91,1.91H9.14a1.9,1.9,0,0,1-1.91-1.91V13a1.9,1.9,0,0,1,1.91-1.9H12A4.78,4.78,0,0,0,16.77,6.27Z"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>