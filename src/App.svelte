<script>
	import Articles from './components/Articles.svelte';
	import Header from './components/Header.svelte';
	import MainImage from './components/MainImage.svelte';
	import Footer from './components/Footer.svelte';
</script>

<div>
	<Header/>  
	<MainImage/>
	<Articles/>
	<Footer/>
</div>

<style>
	div {
		margin: 0;
		height: 100vh; 
		width: 100vw;
		background-color:whitesmoke;    
	}
</style> 