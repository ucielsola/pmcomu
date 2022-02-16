<script>
	import EmaiIcon from '$lib/components/emaiIcon.svelte';
	import WhatsappIcon from '$lib/components/whatsappIcon.svelte';
</script>

<div class="links-container">
	<a href="https://wa.link/bje7mw" target="_blank" rel="noopener nofollower"
		><WhatsappIcon fill="#fff" /><span>+54 9 11 4063-6734</span></a
	>

	<a href="mailto:info@pmcomunicaciones.com.ar" target="_blank" rel="noopener nofollower"
		><EmaiIcon fill="#fff" /><span>info@pmcomunicaciones.com.ar</span></a
	>
</div>

<style>
	.links-container {
		display: flex;
		flex-direction: column;
	}

	a {
		display: flex;
		margin-block: 0.5rem;
		color: #fff;
		text-decoration: none;
		font-size: 1rem;
	}
	a span {
		margin-left: 1rem;
	}
</style>
