<script>
let time = new Date();
setInterval(() => {
		time = new Date();
	}, 1000
)
</script>

<svelte:head>
	<title>contents</title>
	<meta name="description" content="contents">
</svelte:head>

<h1>contents this site</h1>

<p>This is the 'contents' page.</p>

<p>{time}</p>