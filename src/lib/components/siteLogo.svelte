<div class="logo-wrapper">
	<img src="/assets/images/logo.webp" alt="PM Logo" />
	<div class="text-wrapper">
		<h1 class="title">Comunicaciones</h1>
		<h2>La comunicación constituye y a la vez fluye como la vida.</h2>
	</div>
</div>

<style>
	.logo-wrapper {
		display: flex;
		flex-direction: column;
		align-items: center;
		padding-inline: 15px;
	}

	img {
		width: 15rem;
	}

	h1 {
		font-size: clamp(2rem, 8vw, 6rem);
		font-weight: 500;
		text-align: center;
		text-transform: uppercase;
	}

	h2 {
		font-family: 'Montserrat';
		/* font-style: italic; */
		font-weight: 400;
		font-size: 1.1rem;
		text-align: center;
	}

	@media screen and (min-width: 1024px) {
		.logo-wrapper {
			flex-direction: row;
			padding-inline: 0;
		}
		h1 {
			font-weight: 400;
			text-align: left;
			text-transform: capitalize;
		}

		h2 {
			text-align: left;
			font-size: 1.55rem;
		}
	}
</style>
