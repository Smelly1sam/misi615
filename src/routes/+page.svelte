<script>
import me from '$lib/images/me.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
	swhiteusa.com
	<br/>
<img src={me} alt="" />
	</h1>

	<p>
		Welcome to my site, where you can see my social media, videos, and other unique technologies. If you enjoy my site, check out these other amazing locations.
<br/>
Technology:
<br/>
<a href="https://www.bleepingcomputer.com/" target="_blank"> https://www.bleepingcomputer.com/</a>
<br/>
Your new front page:
<br/>
<a href="https://www.reddit.com/" target="_blank">https://www.reddit.com/</a>
<br/>
CISA:
<br/>
<a href="https://www.cisa.gov/" target="_blank">https://www.cisa.gov/</a>

​

​
	</p>

	
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
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
	
</style>
