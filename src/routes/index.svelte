
<script>
import Flecha from '../components/Flecha.svelte'
import Persona from '../components/Persona.svelte'
import Botonhver from '../components/Botonhver.svelte'
import Seleccion from '../components/Seleccion.svelte'
import Colores from '../components/Colores.svelte'
</script>

<svelte:head>
	<title>javier es el mejor de todos</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>
<!-- <A/> -->

<div class="h-screen w-full relative">
	<div class="hola flex justify-center pt-8 h-1/6 bg-blue-900 
	text-white">
		<Flecha/>
		<div>elemento centrado</div>
	</div>
	<div class="
	abajo w-full h-5/6 bg-white flex items-center flex-col
	">
		<Persona/>
		<div class=" flex justify-around w-1/2">
			<Seleccion>primero</Seleccion>
			<Seleccion>segundo</Seleccion>
		</div>
		<div class="w-5/6 mt-5 ">
			<p class="mb-5">calma mi heroe sdsdsd</p>
			<div >
				<Botonhver>hola</Botonhver>
				<Botonhver>camaradas</Botonhver>
				<Botonhver>ahah</Botonhver>
			</div>
			<p class="mb-5 mt-8">calma mi heroe sdsdsd</p>
			<div>
				<Botonhver>s</Botonhver>
				<Botonhver>m</Botonhver>
				<Botonhver>l</Botonhver>
				<Botonhver>xl</Botonhver>
			</div>
			<p class="mb-5 mt-8 ">calma mi heroe sdsdsd</p>
			<div>
				<Colores color="bg-blue-500"/>
				<Colores color="bg-orange-500"/>
				<Colores color="bg-lime-500"/>
				<Colores color="bg-teal-500"/>
			</div>
			<p class="mb-5 mt-8 ">calma mi heroe sdsdsd</p>
			<div>
				<Botonhver margin_y>elemental</Botonhver>
				<Botonhver margin_y>elemental</Botonhver>
				<Botonhver margin_y>elemental</Botonhver>
				<Botonhver margin_y>elemental</Botonhver>
				<Botonhver margin_y>elemental</Botonhver>
			</div>
		</div>
	</div>
	<div class="absolute bg-blue-900 w-36 top-0 h-full -z-10"></div>
</div>
<style>
	.hola{
		border-bottom-right-radius: 100px;
	}
	.abajo{
		border-top-left-radius: 100px;
	}
</style>
