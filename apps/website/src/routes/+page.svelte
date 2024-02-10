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
			Esta es una página de ejemplo. <b>Pyedes</b> editarla en:
			<code> apps/website/src/routes/%2Bpage.svelte </code>.
		</p>

		<p>
			Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sint hic veritatis ullam ab, impedit
			vero suscipit, dicta reprehenderit eaque non quae accusamus, ut omnis quos explicabo est modi
			fugiat quidem!
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
