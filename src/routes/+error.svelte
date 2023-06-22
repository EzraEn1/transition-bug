<script>
  // @ts-nocheck
    import { page } from '$app/stores';
    import Layout from '$lib/Layout.svelte';
  </script>
  
  <Layout>
    <h1 >{$page.status}: {$page.error.message}</h1>
    <p>{page.props} doesn't exist!</p>
    <a href='/'>Go Home</a>
    <!-- {@debug} -->
  </Layout>