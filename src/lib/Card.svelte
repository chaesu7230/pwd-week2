<script lang="ts">
	type Props = {
		title: string;
		summary: string;
		href: string;
	};

	let { title, summary, href }: Props = $props();
</script>

<a class="card" href={href}>
	<h3>{title}</h3>
	<p>{summary}</p>
</a>