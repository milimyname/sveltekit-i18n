<script lang="ts">
  import { LL } from "$lib/i18n/i18n-svelte";

  export let data;
</script>

<h1>{$LL.APPLES(data)}</h1>
<a href="/">Back to start</a>
