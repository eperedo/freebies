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

<style lang="scss">
html {
	font-family: Helvetica, sans-serif;
	font-size: 16px;
}

.app-container {
	background-color: #f8f8f8;
}
</style>
