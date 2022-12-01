
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.75,21.28a31.76,31.76,0,0,0-10.75-2,31.76,31.76,0,0,0-10.75,2V4.67A31.76,31.76,0,0,1,12,2.72,31.76,31.76,0,0,1,22.75,4.67Z"/><polyline class="cls-1" points="1.25 17.37 6.14 12.49 10.05 16.4 15.91 10.53 22.75 17.37"/><circle class="cls-1" cx="10.05" cy="8.58" r="1.95"/></svg>
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