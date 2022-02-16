<script>
	let name;
	let email;
	let message;
	let hideForm = false;
	function formSubmit(e) {
		e.preventDefault();
		fetch('https://formsubmit.co/ajax/ucielsola@gmail.com', {
			method: 'POST',
			headers: {
				'Content-Type': 'application/json',
				Accept: 'application/json'
			},
			body: JSON.stringify({
				Nombre: name,
				eMail: email,
				Mensaje: message
			})
		})
			.then((response) => response.json())
			.then((data) => {
				hideForm = true;
			})
			.catch((error) => {
				console.log(error);
			});
	}
</script>

<div class={hideForm ? 'fade-out' : ''}>
	<h3>Dejanos tu consulta</h3>
	<form on:submit={(e) => formSubmit(e)} id="contact">
		<div class="f-group">
			<label for="name">Nombre</label>
			<input
				id="input-name"
				type="text"
				name="name"
				bind:value={name}
				placeholder="Nombre"
				required
			/>
			<label for="email">Email</label>
			<input type="email" name="email" bind:value={email} placeholder="Email" required />
		</div>
		<div class="f-group">
			<label for="message">Mensage</label>
			<textarea
				id=""
				cols="30"
				rows="10"
				name="message"
				bind:value={message}
				placeholder="Mensaje"
				required
			/>
		</div>
		<div class="submit-wrapper">
			<input type="submit" value="Enviar" />
		</div>
	</form>
</div>

<style>
	/* .fade-in {
		-webkit-animation: fade-in 0.5s cubic-bezier(0.39, 0.575, 0.565, 1) 1.21s both;
		animation: fade-in 0.5s cubic-bezier(0.39, 0.575, 0.565, 1) 1.21s both;
	} */

	form,
	.f-group {
		display: flex;
		flex-direction: column;
	}

	label {
		display: none;
	}

	input,
	textarea {
		padding: 1rem;
		margin-bottom: 0.5rem;
		border: none;
		border-radius: var(--border-radius);
		font-family: var(--body-ff);
	}

	input[type='submit'] {
		padding: 0.3rem 0.7rem;
		color: #fff;
		border: 2px solid #fff;
		border-radius: var(--border-radius);
		box-shadow: var(--box-shadow);
		background-color: var(--highlight);
	}

	input[type='submit']:active {
		box-shadow: none;
	}

	@media screen and (min-width: 1024px) {
		.f-group {
			flex-direction: row;
		}
		input,
		textarea {
			margin-inline: 0.5rem;
		}

		textarea {
			width: 100%;
		}
		
	}
</style>
