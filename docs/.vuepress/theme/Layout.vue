<script setup>
import ParentLayout from '@vuepress/theme-default/lib/client/layouts/Layout.vue';
</script>

<template>
	<ParentLayout>
		<template #page-bottom>
			<div class="center">Made with ♥ and Vuepress</div>
		</template>
	</ParentLayout>
</template>

<script>
export default {
	name: 'theme',
};
</script>

<style lang="css">
.center {
	text-align: center;
}
</style>
