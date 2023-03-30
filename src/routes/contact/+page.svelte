<script>
import pc from '$lib/images/comp.jpg';
</script>

<svelte:head>
	<title>Contact Me</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>

<h1>Contact Me</h1>
<p>
My LinkedIn:
<br/>
<a href="https://www.linkedin.com/in/samuel-white-450b13179/" target="_blank">https://www.linkedin.com/in/samuel-white-450b13179/</a>
<br/>
My Twitter:
<br/>
<a href="https://twitter.com/SamuelWhiteUSA" target="_blank">https://twitter.com/SamuelWhiteUSA</a>
<br/>
My Email:
<br/>
<a href="mailto:Whites36@ferris.edu" target="_blank">Whites36@ferris.edu</a>
<br/>
​<br/>
<br/>
You can see my Youtube channel below
<br/>
<br/>

</p>
<div class="video">
<iframe width="1920" height="778" src="https://www.youtube.com/embed/n0eRkJxi-dA" title="how the hack works" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
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
		font-size: 2rem;
	}

.video {
    position: relative;
    max-width: 100%;
    padding-top: 56.25%;
    width: 100%;
}

.video > iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
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
