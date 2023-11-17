<script>
  import PageHeader from "../lib/components/PageHeader.svelte";
  let name = 1
 </script>


 <PageHeader pageNumber= {name+1} />
 <h1>Welcome to SvelteKit</h1>
 <p>Visit {name} <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
