<template>
	<main id="app" class="app-container">
		<freebies />
	</main>
</template>

<script>
import Freebies from './components/Freebies';

export default {
	name: 'app',
	components: {
		Freebies,
	},
};
</script>

<style lang="scss" scoped>
.app-container {
	align-items: center;
	background-color: #f8f8f8;
	display: flex;
	height: 100%;
	justify-content: center;
}
</style>
