<template>
	<section class="freebies-container">
		<freebies-avatar></freebies-avatar>
		<freebies-form></freebies-form>
	</section>
</template>

<script>
import FreebiesAvatar from './Avatar';
import FreebiesForm from './Form';

export default {
	name: 'freebies',
	components: {
		FreebiesAvatar,
		FreebiesForm,
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


