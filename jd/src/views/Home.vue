<template>
	<div class="home">
		<search-bar></search-bar>
		<div class="name" style="height: 500px;background-color: green;"></div>
		<tab-bar></tab-bar>
	</div>
</template>

<script>
	import SearchBar from "@/components/SearchBar.vue";
	import TabBar from "@/components/TabBar.vue";

	
	export default {
		data: function() {
			return {};
		},
		methods: {},
		props: [],
		watch: {},
		computed: {},
		components:{
			SearchBar,
			TabBar
		}
	}
</script>