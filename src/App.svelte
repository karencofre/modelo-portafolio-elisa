<script>
	import Navigation from './components/Navigation.svelte';
	import Landing from './components/Landing.svelte';
	import Share from './components/Share.svelte';
	import Project from './components/Project.svelte';
	import Comment from './components/Comment.svelte';
	import Form from './components/Form.svelte';
	import Footer from './components/Footer.svelte';
</script>
<style>
	:global(body){
		background: rgb(255,208,168);
background: radial-gradient(circle, rgba(255,208,168,1) 0%, rgba(251,170,158,1) 100%);
	}
</style>

 
<Navigation />
<Landing />
<Share />
<Project title="Leonidasesteban.com" image_project="../assets/img-project1.png" description="Accede a más de 120 proyectos que te ayudarán a mejorar 
tus habilidades como desarrollador Front-End."/>
<Comment image_profile="../assets/user-0.png" comment='"Elisa ha sido de gran ayuda para acelerar ciertos esfuerzos de desarrollo. Lo que nos hubiera llevado 6 meses solo les llevó 1,5 meses ".' source_text="LEONIDAS ESTEBAN / COFUNDADOR Y CEO LEONIDASESTEBAN.COM"/>
<Project title="MARVOL" image_project="../assets/img-project2.png" description="Es el sitio oficial de Marvol Entertainment. Explore películas, personajes, cómics, programas de televisión, videos y más oficiales de Marvol."/>
<Comment image_profile="../assets/user-1.png" comment='"Elisa ha superado mis expectativas desde el diseño hasta el desarrollo".' source_text="JASON LOPEZ / COFUNDADOR Y CEO MARVOL" />

<Project title="NETNET" image_project="../assets/img-project3.png" description="Es el sitio oficial de Marvol Entertainment. Explore películas, personajes, cómics, programas de televisión, videos y más oficiales de Marvol."/>

<Comment image_profile="../assets/user-2.png" comment='"Por primera vez en la historia de nuestra empresa, aparecimos en todas las plataformas en las que trabajamos".' source_text="MARCO CORTEZ / NETNET"/>

<Form/>
<Footer/>
 