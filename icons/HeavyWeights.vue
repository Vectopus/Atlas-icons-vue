
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="5.29" y1="1.46" x2="5.29" y2="9.13"/><line class="cls-1" x1="8.17" y1="0.5" x2="8.17" y2="10.08"/><line class="cls-1" x1="5.29" y1="1.46" x2="5.29" y2="9.13"/><line class="cls-1" x1="8.17" y1="0.5" x2="8.17" y2="10.08"/><line class="cls-1" x1="18.71" y1="9.13" x2="18.71" y2="1.46"/><line class="cls-1" x1="15.83" y1="10.08" x2="15.83" y2="0.5"/><line class="cls-1" x1="18.71" y1="9.13" x2="18.71" y2="1.46"/><line class="cls-1" x1="15.83" y1="10.08" x2="15.83" y2="0.5"/><line class="cls-1" x1="2.42" y1="5.29" x2="5.29" y2="5.29"/><line class="cls-1" x1="8.17" y1="5.29" x2="15.83" y2="5.29"/><line class="cls-1" x1="18.71" y1="5.29" x2="21.58" y2="5.29"/><line class="cls-1" x1="3.38" y1="12.96" x2="3.38" y2="22.54"/><line class="cls-1" x1="6.25" y1="12" x2="6.25" y2="23.5"/><line class="cls-1" x1="3.38" y1="12.96" x2="3.38" y2="22.54"/><line class="cls-1" x1="6.25" y1="12" x2="6.25" y2="23.5"/><line class="cls-1" x1="20.63" y1="22.54" x2="20.63" y2="12.96"/><line class="cls-1" x1="17.75" y1="23.5" x2="17.75" y2="12"/><line class="cls-1" x1="20.63" y1="22.54" x2="20.63" y2="12.96"/><line class="cls-1" x1="17.75" y1="23.5" x2="17.75" y2="12"/><line class="cls-1" x1="0.5" y1="17.75" x2="3.38" y2="17.75"/><line class="cls-1" x1="6.25" y1="17.75" x2="17.75" y2="17.75"/><line class="cls-1" x1="20.63" y1="17.75" x2="23.5" y2="17.75"/></svg>
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