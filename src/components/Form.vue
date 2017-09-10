<template>
	<section class="form-wrapper">
		<form name="frm" class="form-container">
			<div class="form-section">
				<label for="name">Name</label>
				<input id="name" type="text" placeholder="Foo Bar" />
			</div>
			<div class="form-section">
				<label for="date-of-birth">Date of Birth</label>
				<input id="date-of-birth" type="date" placeholder="01/01/2018" />
			</div>
			<div class="form-section">
				<label for="email">Email</label>
				<input id="email" type="email" placeholder="foo@bar.com" />
			</div>
			<div class="form-section">
				<label for="mobile">Mobile</label>
				<input id="mobile" type="tel" placeholder="982389212" />
			</div>
			<div class="form-section">
				<label for="customer">Customer ID</label>
				<input id="customer" type="text" placeholder="553-CSD1" />
			</div>
			<div class="form-section">
				<picture>
					<img src="/static/img/female.png" alt="Freebies female" />
				</picture>
				<picture>
					<img src="/static/img/male.png" alt="Freebies male" />
				</picture>
			</div>
		</form>
	</section>
</template>

<script>
export default {
	name: 'freebies-form',
};
</script>

<style lang="scss" scoped>
.form-wrapper {
	background: map-get($colors, white);
	border-radius: 0 21.25px 21.25px 0;
	padding-top: 10%;
}

.form-container {
	align-items: center;
	display: flex;
	flex-direction: column;
	justify-content: center;

	.form-section {

		display: flex;
		margin-bottom: 5%;

		label {
			font-size: em(7.41);
			width: 70px;
		}

		input[type="text"],
		input[type="email"],
		input[type="tel"],
		input[type="date"] {
			background: rgba(245, 248, 249, 0.30);
			border: 0 solid #CBD7DD;
			border-radius: 2.64px;
			font-size: em(7.41);
		}
	}
}
</style>


