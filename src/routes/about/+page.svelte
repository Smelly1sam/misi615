<script>
import pc from '$lib/images/comp.jpg';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>

<h1>About Me</h1>
<div id="overlay">
 <img src={pc} alt=""/>
 <div>
   
   
   <p>I have been a technology enthusiast my whole life. I enjoy getting into the details and tinkering with what I can. I graduated from Ferris State University and am currently enrolled there for my master's degree. My career in cybersecurity has allowed me to meet people from different backgrounds. This has enriched my life in seeing different perspectives and helped me create a better security posture that everyone can understand.​</p>
 </div>
</div>
	
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
		font-family:Impact;
	}

	p {
		text-align:center;
		color:white;
		text-shadow:1px 1px 2px black;
		font-size: 2rem;
	}

#overlay {
   position: relative;
}

#overlay > img {
z-index: 100;
   position: absolute;
   top: 0;
   left: 0;
   min-width: 100%;
   min-height: 100%;
   width: 100%;
   display: block;
}

#overlay > div {
position: relative;
   z-index: 200;
   margin: 0 auto;
   text-align: center;
   padding:2rem;
}
	
</style>
