<template>
	<section class="avatar-container">
		<p>Avatar</p>
	</section>
</template>

<script>
export default {
	name: 'freebies-avatar',
};
</script>

<style lang="scss" scoped>
.avatar-container {
	// font-size: em(32);
	background: map-get($colors, yellow);
	border-radius: 21.25px 0 0 21.25px;
}
</style>
