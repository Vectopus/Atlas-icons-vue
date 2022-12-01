
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.52,19.63h0a2.86,2.86,0,0,1-2.87,2.87H4.35a2.86,2.86,0,0,1-2.87-2.87h0a1.9,1.9,0,0,1,1.91-1.91H9.13l1,1h3.82l1-1h5.74A1.9,1.9,0,0,1,22.52,19.63Z"/><path class="cls-1" d="M16.78,5.28H18.7A1.92,1.92,0,0,1,20.61,7.2V17.72"/><path class="cls-1" d="M3.39,17.72V7.2A1.92,1.92,0,0,1,5.3,5.28H7.22"/><circle class="cls-1" cx="12" cy="5.28" r="2.87"/><line class="cls-1" x1="12" y1="2.41" x2="12" y2="0.5"/><line class="cls-1" x1="12" y1="10.07" x2="12" y2="8.15"/><line class="cls-1" x1="9.51" y1="3.85" x2="7.86" y2="2.89"/><line class="cls-1" x1="16.14" y1="7.67" x2="14.49" y2="6.72"/><line class="cls-1" x1="16.14" y1="2.89" x2="14.49" y2="3.85"/><line class="cls-1" x1="9.51" y1="6.72" x2="7.86" y2="7.67"/></svg>
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