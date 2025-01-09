<template>
    <div class="w-full">
        <Patients />
    </div>
</template>
<script setup>  
import jsonData from '../assets/data/data.json';
const patients = ref(jsonData.patients);
</script>

