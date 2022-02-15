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
			<input id="input-name" type="text" name="name" bind:value={name} required />
			<input type="email" name="email" bind:value={email} required />
		</div>
		<div class="f-group">
			<textarea id="" cols="30" rows="10" name="message" bind:value={message} required />
		</div>
		<div class="submit-wrapper">
			<input type="submit" value="Enviar" />
		</div>
	</form>
</div>

<div class={!hideForm ? 'fade-in' : ''}>
	<h3>Gracias {name} por tu consulta!</h3>
</div>

<style>
	.fade-in {
		-webkit-animation: fade-in 0.5s cubic-bezier(0.39, 0.575, 0.565, 1) 1.21s both;
		animation: fade-in 0.5s cubic-bezier(0.39, 0.575, 0.565, 1) 1.21s both;
	}
</style>
