<script>
	import BottomDivider from '$lib/components/bottomDivider.svelte';
	import ContactForm from '$lib/components/contactForm.svelte';
	import EmaiIcon from '$lib/components/emaiIcon.svelte';
	import Image from '$lib/components/image.svelte';
	import SiteLogo from '$lib/components/siteLogo.svelte';
	import TopDivider from '$lib/components/topDivider.svelte';
	import WhatsappFab from '$lib/components/whatsappFAB.svelte';
	import WhatsappIcon from '$lib/components/whatsappIcon.svelte';

	import IntersectionObserver from 'svelte-intersection-observer';

	let element;
	let intersecting;
</script>

<WhatsappFab />

<IntersectionObserver {element} bind:intersecting threshold={0}>
	<header bind:this={element} class:intersecting>
		<SiteLogo />
		<BottomDivider />
	</header>
</IntersectionObserver>

<main>
	<section>
		<article class="margin-right">
			<h3>Comunicación, Innovación, Estrategia</h3>
			<p>
				La comunicación estratégica, integral y orgánica es un intangible que influye en los
				productos, servicios y crear valor.
			</p>
			<p>
				En el actual contexto volátil e incierto, lleno de complejidad y ambigüedad creciente, el
				liderazgo, la comunicación y el uso de la tecnología amplían las perspectivas y los
				aprendizajes de nuevas capacidades, para liderar entornos flexibles y empoderados.
			</p>
			<p>
				Creamos y facilitamos para que su mensaje llegue correctamente a los públicos que deben
				recibirlo.
			</p>
		</article>
		<Image src="/assets/images/img-1.webp" alt="PM Comunicaciones" />
	</section>

	<section class="bg-primary">
		<article class="margin-left">
			<h3>QUIÉNES SOMOS</h3>
			<h4>
				PM Comunicaciones es una empresa de asesoramiento en diseño y ejecución de estrategias de
				comunicación y liderazgo.
			</h4>
			<p>
				Nos dirigimos a marcas, personas en puestos de liderazgo, empresas, organizaciones
				gubernamentales y no gubernamentales.
			</p>
			<p>
				Somos aliados en el de desafío de fortalecer su identidad, haciendo visible la gestión,
				cultura, filosofía y responsabilidad social, en definitiva potenciando el valor de la propia
				trayectoria.
			</p>
		</article>
		<Image src="/assets/images/img-2.webp" alt="PM Comunicaciones" />
	</section>

	<section>
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN DIGITAL</h3>
				<h4>
					Logramos el posicionamiento a través de las plataformas virtuales, proporcionando una
					comunicación clara y asertiva.
				</h4>
				<p>
					Las Nuevas Tecnologías de la Información cambiaron radicalmente las formas, modos, tiempos
					y canales de comunicación de las organizaciones y empresas. La comunicación digital es un
					gran reto, pero también una oportunidad. Se convirtieron en una herramienta eficaz de
					gestión, innovación, buen servicios y productividad.
				</p>
				<p>
					Creamos, organizamos y gestionamos los contenidos para adaptarlos comunicativamente a cada
					tipo de red social y les damos presencia global con la traducción a diferentes idiomas
					como el inglés, alemán o portugués.
				</p>
			</article>
			<Image src="/assets/images/img-3.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row">
			<Image src="/assets/images/img-4.webp" alt="PM Comunicaciones" />
			<article class="margin-left">
				<h4>Creación, gestión y difusión de contenidos digitales</h4>
				<ul>
					<li>Manejo de redes sociales</li>
					<li>Creación, gestión y difusión de contenidos digitales</li>
					<li>Desarrollo y diseño de Landing Pages y Webs</li>
					<li>Diseño y optimización de tiendas online</li>
					<li>Posicionamiento online de la marca</li>
					<li>Publicidad en Facebook, Instagram, Google y Linkedin</li>
				</ul>
			</article>
		</div>
	</section>
	<section class="bg-primary">
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN EMPRESARIAL</h3>
				<h4>Ayudamos a tu empresa a generar valor sea cual sea el nivel de madurez digital</h4>
				<p>
					La visión estratégica de la comunicación corporativa permite la construir la interacción,
					dialogo y reconocimiento mutuo que incrementa y consolida la imagen y reputación de la
					empresa u organización. Generamos mayor valor intangible al consolidar la confianza de las
					mismas por sus públicos de interés.
				</p>
			</article>
			<Image src="/assets/images/img-5.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row">
			<Image src="/assets/images/img-6.webp" alt="PM Comunicaciones" />
			<article class="margin-left">
				<h4>Identidad e imagen corporativa</h4>
				<ul>
					<li>Desarrollo de marca</li>
					<li>Posicionamiento de Imagen</li>
					<li>Comunicación estratégica</li>
					<li>Gestión de contenidos</li>
					<li>Manejo de redes</li>
					<li>Entrenamiento y coaching en liderazgo</li>
				</ul>
			</article>
		</div>
	</section>
	<section>
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN POLÍTICA</h3>
				<h4>Lo que no se comunica, no existe.</h4>
				<p>
					Hoy el éxito de cualquier campaña electoral o de política pública se sustenta en el diseño
					y ejecución de una estrategia de comunicación planificada, con objetivos claros, medios de
					difusión adecuados, mensajes concretos y públicos debidamente definidos.
				</p>
			</article>
			<Image src="/assets/images/img-7.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row">
			<Image src="/assets/images/img-8.webp" alt="PM Comunicaciones" />
			<article class="margin-left">
				<h4>Diseño y desarrollo de estrategia comunicativa</h4>
				<ul>
					<li>Análisis de entorno</li>
					<li>Liderazgo</li>
					<li>Manejo y posicionamiento de imagen</li>
					<li>Estrategia y líneas de comunicación</li>
					<li>Estrategia digital</li>
					<li>Asesoramiento de prensa</li>
					<li>Estrategia digital</li>
				</ul>
			</article>
		</div>
	</section>
	<section class="bg-secondary">
		<article class="margin-right">
			<h3>TEAM</h3>
			<h4>
				Nos reta la creatividad, la innovación, la calidad y entrega de resultados tangibles.
				Priorizamos el trabajo en equipo como motor del crecimiento y generación de valor.
			</h4>
			<p>
				Somos un equipo interdisciplinario de programadores, músicos, politólogos, lingüistas,
				filósofos, expertos en comunicación, branding y marketing digital, pensando para vos.
			</p>
		</article>
		<Image src="/assets/images/img-9.webp" alt="PM Comunicaciones" />
	</section>
</main>

<footer>
	<TopDivider />
	<div>
		<h3>PM Comunicaciones</h3>
		<ul>
			<li>
				<a href="https://wa.link/bje7mw" target="_blank" rel="noopener nofollower"
					><WhatsappIcon />+54 9 11 4063-6734</a
				>
			</li>
			<li>
				<a href="mailto:info@pmcomunicaciones.com.ar" target="_blank" rel="noopener nofollower"
					><EmaiIcon />info@pmcomunicaciones.com.ar</a
				>
			</li>
		</ul>
	</div>
	<ContactForm />
</footer>

<style>
	header {
		position: relative;
		display: flex;
		align-items: flex-end;
		justify-content: center;
		padding-bottom: 20vh;
		min-height: 95vh;
		background-image: url('/assets/images/header-bg.webp');
		background-repeat: no-repeat;
		background-size: cover;
		background-attachment: scroll;
		background-position: bottom;
		font-family: var(--title-ff);
	}

	header.intersecting {
		background-attachment: fixed;
	}

	main {
		position: relative;
	}
	section {
		display: flex;
		flex-direction: column;
		padding-block: 2rem;
		padding-inline: 1.5rem;
	}

	footer {
		background-color: var(--highlight);
	}

	h3 {
		font-family: var(--title-ff);
		text-align: center;
		font-size: 2.2rem;
		font-weight: 400;
		line-height: 1em;
		padding-block-end: 1.5rem;
	}

	h4 {
		padding-block-end: 1.5rem;
		font-size: 1.07rem;
		font-weight: 600;
		font-family: var(--body-ff);
	}

	p,
	ul,
	a {
		font-size: 1.07rem;
		font-weight: 300;
		font-family: var(--body-ff);
	}

	p {
		padding-block-end: 1.5rem;
	}

	.margin-right {
		margin-right: 1.8rem;
	}
	.margin-left {
		margin-left: 1.8rem;
	}

	.bg-primary {
		background-color: var(--primary-color);
	}
	.bg-secondary {
		background-color: var(--secondary-color);
	}

	@media screen and (min-width: 1024px) {
		section {
			display: flex;
			justify-content: center;
		}

		article {
			flex-basis: 50%;
		}

		h3 {
			text-align: left;
			font-size: 2.5rem;
		}

		h4 {
			font-size: 1.37rem;
		}

		p,
		ul,
		a {
			font-size: 1.37rem;
		}
	}
</style>
