<template>
	<div id="app">    
		<Header/>
		<div class="container mx-auto">
			<HorizontalTabs/>
		</div>
	</div>
</template>

<script>
import Header from './components/Header.vue'
import HorizontalTabs from './components/HorizontalTabs.vue'
export default {
	name: 'App',
	components: {
		Header,
		HorizontalTabs
	}
}
</script>

<style>
*{
	margin:0;
}
</style>
