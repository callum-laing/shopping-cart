<script>
    import Header from './Header.svelte';
    import './global.css';
	import { page } from '$app/stores';
	$: path = $page.url.pathname;
</script>

<Header />
<slot />