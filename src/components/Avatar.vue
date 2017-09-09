<template>
	<section class="avatar-container">
		<div>
			<div class="avatar-circle">
				<picture>
					<source srcset="/static/img/avatar.webp">
					<img src="/static/img/avatar.png" alt="Freebies Avatar" class="avatar-image" />
				</picture>
			</div>
		</div>
		<p class="title">Let's get you set up</p>
		<p class="subtitle">It should only take a couple of minutes to pair with your watch</p>
		<picture>
			<div class="greater-circle">
				<source srcset="/static/img/greater-2x.webp">
				<img src="/static/img/greater-2x.png" alt="Freebies Greater" width="32" height="32" />
			</div>
		</picture>
	</section>
</template>

<script>
export default {
	name: 'freebies-avatar',
};
</script>

<style lang="scss" scoped>
.avatar-container {
	align-items: center;
	background: map-get($colors, yellow);
	border-radius: 21.25px 0 0 21.25px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	width: 276px;

	p {
		color: map-get($colors, grey);
		text-align: center;
	}
}

.avatar-circle {
	background: map-get($colors, orange);
	border-radius: 50%;
	height: 118px;
	position: relative;
	width: 118px;
}

.avatar-image {
	border-radius: 50%;
	left: -24%;
	position: absolute;
	top: -30%;
}

.greater-circle {
	background-color: map-get($colors, black);
	border-radius: 50%;
	height: 32px;
	margin-top: 33px;
	width: 32px;
}

.subtitle {
	font-family: Helvetica-Light;
	font-size: em(11);
	line-height: 13.81px;
	max-width: 175px;
}

.title {
	font-size: em(18);
}
</style>
