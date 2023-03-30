<script>
import money from '$lib/images/money.jpg';
</script>

<svelte:head>
	<title>G-Analytics</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>

<h1>Google Analytics</h1>
<p>
Google Analytics allows you to track the traffic to your site. You can follow where they go and what content gives you the most clicks. This can be beneficial when trying to boost your numbers.
<br/>
<a href="https://www.youtube.com/watch?v=P3V01bDbIR0" target="_blank">https://www.youtube.com/watch?v=P3V01bDbIR0</a>
</p>
<img src={money} alt="" />
	
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

section img {
   max-width:80%;
   height:auto;
}
	
</style>
