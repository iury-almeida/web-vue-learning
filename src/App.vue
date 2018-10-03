<template>

	<div>

		<h2>{{ titulo }}</h2>

		<ul>
			<li v-for="foto of fotos">
				<img :src="foto.url" :alt="foto.titulo">
			</li>
		</ul>
	</div>

</template>

<script>
export default {

	data(){
		return {
			titulo: 'Olá Paz uzu',
			fotos: [
				{
					url: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/PazuzuDemonAssyria1stMillenniumBCE.jpg/200px-PazuzuDemonAssyria1stMillenniumBCE.jpg',
					titulo: 'Pazuzu'
				},
				{
					url: 'https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/PazuzuDemonAssyria1stMillenniumBCE.jpg/200px-PazuzuDemonAssyria1stMillenniumBCE.jpg',
					titulo: 'Pazuzuss'
				}	
			]
		}
	}
}
</script>
	
<style lang="scss">

</style>
