
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.17,3.55h1.89a3.78,3.78,0,0,1,3.78,3.78V9.22a0,0,0,0,1,0,0H12.94A3.78,3.78,0,0,1,9.17,5.44V3.55A0,0,0,0,1,9.17,3.55Z" transform="translate(8.03 -6.62) rotate(45)"/><path class="cls-1" d="M12,8.27h1.89A3.78,3.78,0,0,1,17.66,12v1.89a0,0,0,0,1,0,0H15.78A3.78,3.78,0,0,1,12,10.16V8.27A0,0,0,0,1,12,8.27Z" transform="translate(25.94 -3.73) rotate(90)"/><path class="cls-1" d="M6.34,8.27H8.22A3.78,3.78,0,0,1,12,12v1.89a0,0,0,0,1,0,0H10.11a3.78,3.78,0,0,1-3.78-3.78V8.27A0,0,0,0,1,6.34,8.27Z"/><path class="cls-1" d="M12,13.94h1.89a3.78,3.78,0,0,1,3.78,3.78V19.6a0,0,0,0,1,0,0H15.78A3.78,3.78,0,0,1,12,15.83V13.94A0,0,0,0,1,12,13.94Z" transform="translate(31.6 1.94) rotate(90)"/><path class="cls-1" d="M6.34,13.94H8.22A3.78,3.78,0,0,1,12,17.71V19.6a0,0,0,0,1,0,0H10.11a3.78,3.78,0,0,1-3.78-3.78V13.94A0,0,0,0,1,6.34,13.94Z"/><line class="cls-1" x1="12" y1="23.38" x2="12" y2="10.16"/></svg>
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