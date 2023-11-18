<script>
  import { setContext } from "svelte";

  console.log("/ (layout)");
  setContext("data", 123);
</script>

<slot />
