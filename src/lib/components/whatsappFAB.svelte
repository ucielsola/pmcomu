<script>
	import WhatsappIcon from './whatsappIcon.svelte';
</script>

<button title="Contactanos por WhatsApp">
	<a
		href="https://web.whatsapp.com/send?phone=541156122325&text="
		target="_blank"
		rel="noopener noreferrer"><WhatsappIcon fill="#fff" /></a
	></button
>

<style>
	button {
		cursor: pointer;
		position: fixed;
		bottom: 1.5rem;
		right: 1.5rem;
		z-index: 100;
		display: grid;
		place-content: center;
		width: 4rem;
		height: 4rem;
		appearance: none;
		background-color: var(--whatsapp);
		border: none;
		box-shadow: var(--box-shadow);
		border-radius: 100%;
		-webkit-animation: slide-in-right 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
		animation: slide-in-right 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
	}

	@-webkit-keyframes slide-in-right {
		0% {
			-webkit-transform: translateX(1000px);
			transform: translateX(1000px);
			opacity: 0;
		}
		100% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
			opacity: 1;
		}
	}
	@keyframes slide-in-right {
		0% {
			-webkit-transform: translateX(1000px);
			transform: translateX(1000px);
			opacity: 0;
		}
		100% {
			-webkit-transform: translateX(0);
			transform: translateX(0);
			opacity: 1;
		}
	}
</style>
