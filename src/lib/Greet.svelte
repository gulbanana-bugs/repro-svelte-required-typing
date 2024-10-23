<script lang="ts">
    import type { Snippet } from 'svelte';

    let {whom}: {whom: Snippet} = $props();
</script>

<p>Hello, {@render whom()}.</p>