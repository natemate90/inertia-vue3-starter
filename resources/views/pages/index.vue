
<template layout>
	<div>
        <h1 class="text-3xl font-bold">{{page}}</h1>
	</div>
</template>

<script setup lang="ts">
defineProps<{
    page: string
}>()
</script>
