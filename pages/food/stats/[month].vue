<script lang="ts" setup>
    const route = useRoute();
    const month = route.params.month;

</script>
<template>
    <div>
        <p>O mes é {{ month }}</p>
    </div>
</template>