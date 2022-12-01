
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.52,12a9.55,9.55,0,0,0,5.4,8.59l.33,1.91h7.64l.33-1.91a9.73,9.73,0,0,0,2.6-1.84A9.56,9.56,0,0,0,20.61,12Z"/><line class="cls-1" x1="4.39" y1="1.5" x2="23.48" y2="1.5"/><line class="cls-1" x1="4.39" y1="5.32" x2="23.48" y2="5.32"/><line class="cls-1" x1="6.3" y1="3.41" x2="6.3" y2="12"/><line class="cls-1" x1="9.16" y1="3.41" x2="9.16" y2="12"/><line class="cls-1" x1="12.02" y1="3.41" x2="12.02" y2="12"/></svg>
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