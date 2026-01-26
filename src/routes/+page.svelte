<script>
	import { SvelteFlow, Background, BackgroundVariant } from '@xyflow/svelte';
	import Node from '$lib/ui/Node.svelte';
	import Header from '$lib/ui/Header.svelte';
	import '@xyflow/svelte/dist/style.css';
</script>

<svelte:head>
	<title>AID Home</title>
</svelte:head>

<div class="grid-bg"></div>

<Header lastCommit="2 days ago" author="CamillaS" />
<div class="main">
	<Node
		nodeText="The Norwegian Centre on AI for Decisions (aiD) is a premier research hub dedicated to advancing the role of artificial intelligence in complex decision-making processes. As a cornerstone of the Research Council of Norway’s (RCN) AI portfolio, aiD bridges technological, organizational, and human-centric gaps to foster a society where AI-driven value creation is safe and ethical."
	/>
</div>

<style>
	.main {
		position: absolute;
		top: 0;
		bottom: 0;
		left: 200;
		right: 0;
	}
	.grid-bg {
		position: fixed;
		inset: 0;
		background-color: #050505;
		background-image: radial-gradient(#3f3f3f 1px, transparent 1px);
		background-size: 24px 24px;
		z-index: -1;
	}
</style>
