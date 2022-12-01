
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="reciept_alternatif" data-name="reciept alternatif"><line class="cls-1" x1="10" y1="7.5" x2="18" y2="7.5"/><line class="cls-1" x1="10" y1="11.5" x2="18" y2="11.5"/><line class="cls-1" x1="10" y1="15.5" x2="18" y2="15.5"/><line class="cls-1" x1="8" y1="7.5" x2="6" y2="7.5"/><line class="cls-1" x1="8" y1="11.5" x2="6" y2="11.5"/><line class="cls-1" x1="8" y1="15.5" x2="6" y2="15.5"/><polygon class="cls-2" points="4 22.5 6.66 20.5 9.33 22.5 11.99 20.5 14.66 22.5 17.33 20.5 20 22.5 21 21.5 21 1.5 3 1.5 3 21.5 4 22.5"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>