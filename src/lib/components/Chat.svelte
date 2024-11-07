<script lang="ts">
	import OpenAI from 'openai';

	type Props = { client: OpenAI };
	let { client }: Props = $props();
</script>
