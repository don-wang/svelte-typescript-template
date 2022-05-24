<script lang="ts">
  import { Button } from "attractions";
</script>

<main>
  <h1>Hello</h1>
  <p>Svelte Typescript Template</p>
  <Button outline>Button</Button>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
