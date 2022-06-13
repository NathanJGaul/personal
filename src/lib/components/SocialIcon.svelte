<script>
    import Fa from 'svelte-fa/src/fa.svelte';

    export let icon;
    export let url;
</script>

<a class="aspect-square text-slate-200 rounded-full border border-slate-200 p-4 mx-1 transition hover:scale-105" href={url} target="#blank">
	<Fa icon={icon} size="2x" />
</a>
