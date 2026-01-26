<script lang="ts">
	import '../../routes/layout.css';
	let { lastCommit, author } = $props();
</script>

<div class="header navbar text-gray-200 shadow-sm">
	<div class="navbar-start">
		<span>v0.1</span>
	</div>
	<div class="navbar-center">
		<span>ai:D</span>
	</div>
	<div class="navbar-end">
		<span>Last commit {lastCommit} ago by {author}</span>
	</div>
</div>

<style>
	.header {
		font-family: 'Milling';
	}
</style>
