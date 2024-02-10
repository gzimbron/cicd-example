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
			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est ab corrupti quisquam quos
			aspernatur, ea necessitatibus voluptatum excepturi error. Labore, exercitationem. Optio
			placeat repudiandae quaerat deleniti. Voluptas earum unde nisi!.
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
