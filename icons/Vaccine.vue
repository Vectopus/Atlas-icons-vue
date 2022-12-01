
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="Syringe"><line class="cls-1" x1="17" y1="1" x2="23" y2="7"/><line class="cls-1" x1="19.78" y1="4.22" x2="16.95" y2="7.05"/><line class="cls-1" x1="14.83" y1="9.17" x2="16.95" y2="11.29"/><line class="cls-1" x1="12.71" y1="11.29" x2="14.83" y2="13.41"/><line class="cls-1" x1="12" y1="2" x2="22" y2="12"/><polygon class="cls-1" points="14.5 4.5 6.01 12.99 5.21 16.29 7.71 18.79 11.01 17.99 19.5 9.5 14.5 4.5"/><line class="cls-1" x1="1.64" y1="22.36" x2="6.46" y2="17.54"/><line class="cls-1" x1="10.59" y1="13.41" x2="12.71" y2="15.54"/></g></svg>
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