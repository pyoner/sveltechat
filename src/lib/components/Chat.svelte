<script lang="ts">
	import type { Snippet } from 'svelte';
	import OpenAI from 'openai';

	type Props = { client: OpenAI; children: Snippet };
	let { client, children }: Props = $props();
</script>

{@render children()}
