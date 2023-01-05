<script>
   
    import Account from '$lib/supabase/Account.svelte'
    import Auth from '$lib/supabase/Auth.svelte'
    import Button from "$lib/daisyui/actions/Button.svelte";
    import NavBar from '$lib/daisyui/navigation/NavBar.svelte';
</script>
<svelte:head>
  <title>Supabase + SvelteKit</title>
  <meta name="description" content="SvelteKit using supabase-js v2" />
</svelte:head>

<NavBar />

<h1 class="text-3xl font-bold underline">
    Hello world!
</h1>
<Button btnType="btn-secondary">TEST</Button>