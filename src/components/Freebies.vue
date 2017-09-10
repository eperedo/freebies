<template>
	<section class="freebies-container">
		<freebies-avatar></freebies-avatar>
		<freebies-form></freebies-form>
	</section>
</template>

<script>

export default {
	name: 'freebies',
	components: {
		FreebiesAvatar: () => import('./Avatar'),
		FreebiesForm: () => import('./Form'),
	},
};
</script>

<style lang="scss" scoped>
.freebies-container {
	border-radius: 21.25px 0 0 21.25px;
	display: flex;
	height: 446px;
	width: 680px;
}
</style>


