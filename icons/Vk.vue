
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,7.25c0,2.86,2.86,10.5,10.5,10.5h1.91V14.89h1a6.34,6.34,0,0,1,2.85,2.85H22.5V16.8c-1-1.5-2.55-2.55-3.82-3.82h0a9.79,9.79,0,0,0,2.57-4.53l.3-1.2H17.73l-.1.3A11.3,11.3,0,0,1,14.86,12h-.95V7.25H9.14V8.2l.95,1V13A6,6,0,0,1,6.27,7.25Z"/></svg>
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