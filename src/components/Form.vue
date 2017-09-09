<template>
	<section class="form-container">
		<form name="frm">
			<picture>
				<img src="/static/img/female.png" alt="Freebies female" />
				<img src="/static/img/male.png" alt="Freebies male" />
			</picture>
		</form>
	</section>
</template>

<script>
export default {
	name: 'freebies-form',
};
</script>

<style lang="scss" scoped>
.form-container {
	background: map-get($colors, white);
	border-radius: 0 21.25px 21.25px 0;
}
</style>


