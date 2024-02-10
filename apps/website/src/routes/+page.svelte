<script lang="ts">
	import { Saludo } from '@gzim/demopkg';

	const persona = {
		nombre: 'Gus',
		apellido: 'Zim'
	};
</script>

<h1>Welcome to SvelteKit</h1>
<p>
	{JSON.stringify(persona)}
</p>

<Saludo nombre={persona.nombre}></Saludo>
<!-- <Saludo nombre="{persona.nombre} {persona.apellido}"></Saludo>
 -->
