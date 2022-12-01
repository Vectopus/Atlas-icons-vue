
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.84,6.76a2.75,2.75,0,0,1,2.16,1,2.75,2.75,0,0,1,2.16-1A2.4,2.4,0,0,1,16.75,8.9c0,3.21-4.75,5-4.75,5s-4.75-1.78-4.75-5A2.4,2.4,0,0,1,9.84,6.76Z"/><rect class="cls-1" x="2.5" y="1.55" width="19" height="20.9"/><rect class="cls-1" x="2.5" y="18.65" width="19" height="3.8"/></svg>
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