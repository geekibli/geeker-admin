<template>
	<div class="logo flx-center">
		<img src="@/assets/images/duobian_logo.svg" alt="logo" />
		<span v-show="!isCollapse">多变科技</span>
	</div>
</template>

<script setup lang="ts">
defineProps<{ isCollapse: boolean }>();
</script>

<style scoped lang="scss">
@import "../index.scss";
</style>
