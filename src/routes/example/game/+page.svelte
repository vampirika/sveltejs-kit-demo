<svelte:head>
	<title>Example</title>
	<meta name="description" content="Game page" />
</svelte:head>

<script>
  import Button from '/src/shared/Button.svelte'
</script>

<div class="text-column">
	<h1>Welcome to my maths game</h1>

<Button type="primary">Easy</Button>
<Button type="secondary">Medium</Button>
<Button disabled="true">Hard (disabled)</Button>

</div>