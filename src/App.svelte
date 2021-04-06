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
<Project title="hola1" image_project="" description=""/>
<Comment image_profile="" comment="" source_text="" />
<Project title="hola2" image_project="" description=""/>
<Comment image_profile="" comment="" source_text=""/>
<Project title="hola3" image_project="" description=""/>
<Comment image_profile="" comment="" source_text=""/>
<Form/>
<Footer/>
 