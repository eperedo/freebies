<template>
	<section class="form-wrapper">
		<form name="frm" class="form-container">
			<div class="form-section">
				<label for="name">Name</label>
				<input id="name" type="text" placeholder="Foo Bar" />
			</div>
			<!-- <div class="form-section">
																		<label for="name">Gender</label>
																		<picture>
																			<img src="/static/img/female.png" alt="Freebies female" height="17" width="17" />
																		</picture>
																		<picture>
																			<img src="/static/img/male.png" alt="Freebies male" height="17" width="17" />
																		</picture>
																	</div> -->
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
			<div class="form-section actions">
				<button type="reset" class="btn grey">Cancel</button>
				<button type="submit" class="btn primary">Save</button>
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
	padding: 10% 0 0 10%;
	width: 403.75px;
}

.form-container {
	display: flex;
	flex-direction: column;
	font-size: em(7.41);

	.btn {
		background: #F5F8F9;
		border: none;
		border-radius: 2.64px;
		height: 26.48px;
		text-transform: uppercase;
		width: 79px;

		&.primary {
			background-color: map-get($colors, light-green);
			color: map-get($colors, white);
			margin-left: 7%;
		}
	}

	.form-section {
		align-items: baseline;
		display: flex;
		margin-bottom: 5%;

		&.actions {
			align-self: center;
		}

		label {
			width: 70px;
		}

		input[type="text"],
		input[type="email"],
		input[type="tel"],
		input[type="date"] {
			background: rgba(245, 248, 249, 0.30);
			border: 0 solid #CBD7DD;
			border-radius: 2.64px;
			height: 27px;
			width: 191px;
		}
	}
}
</style>


