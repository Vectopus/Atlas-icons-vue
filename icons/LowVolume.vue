
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.68,10a2.83,2.83,0,0,1,0,4"/><rect class="cls-1" x="1.5" y="8.25" width="4.69" height="7.5"/><polygon class="cls-1" points="13.69 3.56 13.69 20.44 12.05 20.44 6.19 15.75 6.19 8.25 12.05 3.56 13.69 3.56"/></svg>
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