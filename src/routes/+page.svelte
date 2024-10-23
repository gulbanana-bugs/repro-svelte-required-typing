<script>
	import Paragraph from "$lib/Paragraph.svelte";
</script>

<Paragraph>{#snippet children(who)}hello, {who}{/snippet}</Paragraph>