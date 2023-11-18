<script>
  import { setContext } from "svelte";

  console.log("/other (layout)");
  setContext("data", 123);
</script>

<slot />
