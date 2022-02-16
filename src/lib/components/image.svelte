<script>
	import IntersectionObserver from 'svelte-intersection-observer';

	let element;
	let intersecting;
	export let alt;
	export let src;
</script>

<IntersectionObserver {element} bind:intersecting threshold={0}>
	<img bind:this={element} {src} {alt} class:intersecting />
</IntersectionObserver>

<style>
	img {
		max-width: clamp(2rem, 60vw, 320px);
		margin-inline: auto;
		border-radius: var(--border-radius);
		box-shadow: var(--box-shadow);
		opacity: 0;
	}

	img.intersecting {
		-webkit-animation: puff-in-center 0.5s var(--easing) both;
		animation: puff-in-center 0.5s var(--easing) both;
	}
	@-webkit-keyframes puff-in-center {
		0% {
			-webkit-transform: scale(1.03);
			transform: scale(1.03);
			-webkit-filter: blur(4px);
			filter: blur(4px);
			opacity: 0;
		}
		100% {
			-webkit-transform: scale(1);
			transform: scale(1);
			-webkit-filter: blur(0px);
			filter: blur(0px);
			opacity: 1;
		}
	}
</style>
