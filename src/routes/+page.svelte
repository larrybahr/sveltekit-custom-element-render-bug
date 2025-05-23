
<svelte:head>
	<link
		rel="stylesheet"
		href="https://early.webawesome.com/webawesome@3.0.0-alpha.13/dist/styles/themes/default.css"
	/>
	<link
		rel="stylesheet"
		href="https://early.webawesome.com/webawesome@3.0.0-alpha.13/dist/styles/webawesome.css"
	/>
	<script
		type="module"
		src="https://early.webawesome.com/webawesome@3.0.0-alpha.13/dist/webawesome.loader.js"
	></script>
</svelte:head>
<wa-page mobile-breakpoint="900">
	<div slot="banner">banner</div>
	<header slot="header">header</header>
	<header slot="main-header">
		<wa-button variant="contrast" size="large">header main</wa-button>
	</header>
	<main>main</main>
	<footer slot="footer">footer</footer>
</wa-page>
