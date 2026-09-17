<script lang="ts">
	export let title: string;
	export let summary: string;
	export let href: string;
</script>

<a class="card" href={href}>
	<h3>{title}</h3>
	<p>{summary}</p>
</a>