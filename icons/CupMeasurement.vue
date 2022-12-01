
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="measuring_cup" data-name="measuring cup"><path class="cls-1" d="M5.32,1.5H2.45v1L5.32,5.32V19.64A2.86,2.86,0,0,0,8.18,22.5h10.5a2.87,2.87,0,0,0,2.87-2.86V1.5Z"/><line class="cls-1" x1="14.86" y1="6.27" x2="18.68" y2="6.27"/><line class="cls-1" x1="16.77" y1="9.14" x2="18.68" y2="9.14"/><line class="cls-1" x1="14.86" y1="12" x2="18.68" y2="12"/><line class="cls-1" x1="16.77" y1="14.86" x2="18.68" y2="14.86"/><line class="cls-1" x1="14.86" y1="17.73" x2="18.68" y2="17.73"/></g></svg>
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