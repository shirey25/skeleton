<script>
	// The ordering of these imports is critical to your app working properly
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';
	import {AppShell, AppBar} from '../modules.js'
	import {modules} from '../modules.js'

</script>

<svelte:head> </svelte:head>	
	<title>Home</title>
	<AppShell>
		<AppBar />

	<slot></slot>

	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	
		<footer></footer>
	</AppShell>


</style>