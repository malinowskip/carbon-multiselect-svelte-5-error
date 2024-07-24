<script>
  import "carbon-components-svelte/css/g100.css";
  import { MultiSelect } from "carbon-components-svelte";
</script>

<section>
  <p>
    The MultiSelect component below causes the following error to be printed to
    the console: <strong
      >Uncaught (in promise) Svelte error: effect_update_depth_exceeded</strong
    >
  </p>
  <hr />
  <MultiSelect titleText="Test" label="Test" items={[{ id: 1, text: "Foo" }]} />
</section>

<style>
  section {
    max-width: 700px;
    padding: 1rem;
  }
</style>
