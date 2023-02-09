
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 8.18 13.05 10.38 15.41 10.73 13.7 12.45 14.11 14.86 12 13.72 9.89 14.86 10.3 12.45 8.59 10.73 10.95 10.38 12 8.18"/><path class="cls-1" d="M12,22.5s8.59-2.86,8.59-7.64c0-2.86-.95-2.86-.95-5.72a11.65,11.65,0,0,1,.95-4.78l-.95-1.91H15.82A9.92,9.92,0,0,1,12,1.5a9.92,9.92,0,0,1-3.82,1H4.36l-1,1.91a11.65,11.65,0,0,1,1,4.78c0,2.86-1,2.86-1,5.72C3.41,19.64,12,22.5,12,22.5Z"/></svg>
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