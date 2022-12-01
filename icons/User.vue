
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.45,7.23V9.14l5.73,1.91v4.77h0V22.5h1.91L11,16.69a1,1,0,0,1,2,0l.89,5.81h1.91V11.05l5.73-1.91V7.23Z"/><circle class="cls-1" cx="12" cy="4.36" r="2.86"/></svg>
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