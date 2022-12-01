
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.73,22.5H3.27A1.77,1.77,0,0,1,1.5,20.73h0a2.45,2.45,0,0,1,0-.27L3,10.61A2.85,2.85,0,0,1,5.87,8.18H18.13A2.85,2.85,0,0,1,21,10.61l1.52,9.85a2.45,2.45,0,0,1,0,.27h0A1.77,1.77,0,0,1,20.73,22.5Z"/><path class="cls-1" d="M12,1.5h0a5.73,5.73,0,0,1,5.73,5.73v1a0,0,0,0,1,0,0H6.27a0,0,0,0,1,0,0v-1A5.73,5.73,0,0,1,12,1.5Z"/><line class="cls-1" x1="6.27" y1="12" x2="17.73" y2="12"/><line class="cls-1" x1="14.86" y1="14.86" x2="14.86" y2="12"/></svg>
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