<script lang="ts">
	import { Saludo, MensajeCool } from '@gzim/demopkg';

	const persona = {
		nombre: 'Gus',
		apellido: 'Zim'
	};
</script>

<section>
	<MensajeCool>
		<Saludo nombre={persona.nombre}></Saludo>
		<p>
			Esta es una página de ejemplo. Puedes editarla en <code
				>apps/website/src/routes/%2Bpage.svelte</code
			>.
		</p>
	</MensajeCool>
</section>

<style>
	section {
		position: relative;
		max-width: 600px;
		margin: auto;
	}
</style>
