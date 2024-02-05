<template>
    <div>
   <p>Product Details for: {{ id}}</p>
    </div>
</template>

<script setup>
const {id}  = useRoute().params
</script>