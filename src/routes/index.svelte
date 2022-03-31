<script>
	import BottomDivider from '$lib/components/bottomDivider.svelte';
	import ContactForm from '$lib/components/contactForm.svelte';
	import FooterLinks from '$lib/components/footerLinks.svelte';
	import Image from '$lib/components/image.svelte';
	import SiteLogo from '$lib/components/siteLogo.svelte';
	import TopDivider from '$lib/components/topDivider.svelte';
	import WhatsappFab from '$lib/components/whatsappFAB.svelte';
</script>

<WhatsappFab />

<header>
	<SiteLogo />
	<BottomDivider />
</header>

<main>
	<section>
		<article class="margin-right">
			<h3>Comunicación, Innovación, Estrategia</h3>
			<p>
				La comunicación estratégica e integral es un valor intangible que fortalece de manera
				exponencial el impacto de productos, campañas, servicios o ventas.
			</p>
			<p>
				En el actual contexto volátil e incierto, de complejidad y ambigüedad creciente, el
				liderazgo, la comunicación y el uso de la tecnología se posicionan como las herramientas
				fundamentales para liderar entornos flexibles y empoderados.
			</p>
			<p>
				En PM Comunicaciones creamos su mensaje y facilitamos los canales y formatos para que llegue
				correctamente a los públicos que deben recibirlo.
			</p>
		</article>
		<Image src="/assets/images/img-1.webp" alt="PM Comunicaciones" />
	</section>

	<section class="bg-primary reverse">
		<article class="margin-left">
			<h3>QUIÉNES SOMOS</h3>
			<h4>
				PM Comunicaciones es una empresa de asesoramiento en diseño y ejecución de estrategias de
				comunicación.
			</h4>
			<p>
				Nos dirigimos a marcas, personas en puestos de liderazgo, empresas, organizaciones
				gubernamentales y no gubernamentales.
			</p>
			<p>
				Somos aliados en el desafío de fortalecer su identidad, nos encargamos de potenciar el valor
				de la trayectoria recorrida. Visibilizamos la gestión de calidad, la cultura y la filosofía
				de su empresa o entidad.
			</p>
		</article>
		<Image src="/assets/images/img-2.webp" alt="PM Comunicaciones" />
	</section>

	<section class="with-rows">
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN DIGITAL</h3>
				<h4>
					Logramos el posicionamiento a través de las plataformas virtuales, proporcionando una
					comunicación clara y asertiva.
				</h4>
				<p>
					Las nuevas tecnologías de la información cambiaron radicalmente las formas, tiempos y
					canales de comunicación de las organizaciones y empresas. Se convirtieron en una
					herramienta eficaz de gestión, innovación, buenos servicios y productividad. La
					comunicación digital es un gran reto, pero también una oportunidad.
				</p>
				<p>
					Desde PM Comunicaciones creamos contenidos y los gestionamos para adaptarlos
					comunicativamente a cada red social. Además, impulsamos su presencia global mediante la
					traducción a diferentes idiomas: inglés, alemán, y portugués.
				</p>
			</article>
			<Image src="/assets/images/img-4.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row reverse">
			<article class="margin-left">
				<h4>Creación, gestión y difusión de contenidos digitales</h4>
				<ul>
					<li>Posicionamiento online de la marca</li>
					<li>Desarrollo y diseño de Landing Pages y Webs</li>
					<li>Manejo de redes sociales</li>
					<li>Diseño y optimización de tiendas online</li>
					<li>
						Implementación de ChatBots en WhatsApp. Respuestas automáticas. Contactos ilimitados.
					</li>
					<li>Publicidad en Facebook, Instagram, Google y LinkedIn.</li>
				</ul>
			</article>
			<Image src="/assets/images/img-3.webp" alt="PM Comunicaciones" limitHeight={true} />
		</div>
	</section>
	<section class="bg-primary with-rows">
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN EMPRESARIAL</h3>
				<h4>Ayudamos a tu empresa a generar valor sea cual sea su nivel de madurez digital.</h4>
				<p>
					El liderazgo, la comunicación y el uso de la tecnología amplían las perspectivas y los
					aprendizajes de nuevas capacidades.
				</p>
				<p>
					Nuestra visión estratégica de la comunicación corporativa nos permite construir una
					interacción y un diálogo fluido con el público, para que la imagen y reputación de la
					empresa se consoliden.
				</p>
			</article>
			<Image src="/assets/images/img-5.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row reverse">
			<article class="margin-left more">
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
			<Image src="/assets/images/img-6.webp" alt="PM Comunicaciones" />
		</div>
	</section>
	<section class="with-rows">
		<div class="row">
			<article class="margin-right">
				<h3>COMUNICACIÓN POLÍTICA</h3>
				<h4>Lo que no se comunica, no existe.</h4>
				<p>
					Hoy el éxito de cualquier campaña electoral o política pública se sustenta en el diseño y
					ejecución de una estrategia de comunicación planificada.
				</p>
				<p>
					En PM Comunicaciones le brindamos al candidato u entidad un conjunto de acciones pensadas
					a medida, con ejes y objetivos claros, mensajes concretos, públicos definidos y medios de
					difusión adecuados.
				</p>
			</article>
			<Image src="/assets/images/img-7.webp" alt="PM Comunicaciones" />
		</div>
		<div class="row reverse">
			<article class="margin-left">
				<h4>Diseño y desarrollo de estrategia comunicativa</h4>
				<ul>
					<li>Análisis de entorno</li>
					<li>Manejo y posicionamiento de imagen</li>
					<li>Estrategia y líneas de comunicación</li>
					<li>Estrategia digital</li>
					<li>Asesoramiento de prensa</li>
					<li>Coaching para candidatos y armado de equipos</li>
				</ul>
			</article>
			<Image src="/assets/images/img-8.webp" alt="PM Comunicaciones" />
		</div>
	</section>
	<section class="bg-secondary">
		<article class="margin-right">
			<h3>TEAM</h3>
			<h4>
				En PM Comunicaciones la creatividad, la innovación, y el servicio de calidad nos
				caracteriza.
			</h4>
			<p>
				Priorizamos el trabajo en equipo como motor de crecimiento y optimizador de resultados.
				Somos un equipo interdisciplinario de jóvenes programadores, músicos, politólogos,
				filósofos, expertos en comunicación, branding y marketing digital, pensando para usted.
			</p>
		</article>
		<Image src="/assets/images/img-9.webp" alt="PM Comunicaciones" limitHeight={true} />
	</section>
</main>

<footer>
	<TopDivider />
	<div class="footer-content">
		<FooterLinks />
		<ContactForm />
	</div>
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

	main {
		position: relative;
	}
	section {
		display: flex;
		flex-direction: column;
		padding-block: 2rem;
		padding-inline: 1.25rem;
	}

	article {
		padding-block: 1.5rem;
	}

	.row {
		display: flex;
		flex-direction: column;
	}

	footer {
		background-color: var(--highlight);
	}

	.footer-content {
		display: flex;
		flex-direction: column-reverse;
		justify-content: space-evenly;
		margin-blo: 2rem;
		color: #d6d6d6 !important;
		font-family: var(--body-ff) !important;
		max-width: 85vw;
		margin-inline: auto;
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
		padding-block: 1.5rem;
		font-size: 1.07rem;
		font-weight: 600;
		font-family: var(--body-ff);
	}

	p,
	ul {
		font-size: 1.07rem;
		font-weight: 300;
		font-family: var(--body-ff);
		padding-block-end: 1.5rem;
	}

	ul li {
		padding-inline-start: 0.5rem;
		line-height: 1.8;
	}
	/* 
	ul li::marker {
		content: '✓';
	} */

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
			flex-direction: row;
		}

		section.with-rows {
			flex-direction: column;
		}

		.row {
			display: flex;
			flex-direction: row;
			justify-content: center;
		}

		.reverse {
			margin-top: 4rem;
			flex-direction: row-reverse;
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
			padding-block: 0 1.5rem;
		}

		p,
		ul {
			font-size: 1.37rem;
		}
		.margin-right {
			margin-right: 1.8rem;
		}
		.margin-left {
			margin-left: 1.8rem;
		}

		.margin-left.more {
			padding-left: 1.8rem;
		}

		.footer-content {
			flex-direction: row;
		}
	}
</style>
