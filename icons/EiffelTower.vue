
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.61,22.5H15.83a3.83,3.83,0,0,0-7.66,0H3.39l3.83-6.7h9.56Z"/><polygon class="cls-1" points="15.83 15.8 8.17 15.8 9.13 11.98 14.87 11.98 15.83 15.8"/><path class="cls-1" d="M12,.5h0a35.37,35.37,0,0,1-1.81,11.18l-.1.3"/><path class="cls-1" d="M12,.5h0a35.37,35.37,0,0,0,1.81,11.18l.1.3"/><line class="cls-1" x1="10.09" y1="2.41" x2="13.91" y2="2.41"/></svg>
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