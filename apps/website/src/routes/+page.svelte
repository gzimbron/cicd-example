<script lang="ts">
	import { Saludo } from '@gzim/cicdexample';
	import { type Persona } from '@gzim/cicdexample/tipos';
	const persona: Persona = {
		nombre: 'Gus',
		apellido: 'Zim'
	};
</script>

<h1>Welcome to SvelteKit</h1>
<p>
	{JSON.stringify(persona)}
</p>

<Saludo nombre="{persona.nombre} {persona.apellido}"></Saludo>
