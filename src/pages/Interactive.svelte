<script lang="ts">
  import { Button } from '$lib/components/ui/button'
  let clicked = 0
</script>

<Button on:click={() => clicked++}>
  Clicked {clicked}
  {clicked === 1 ? 'time' : 'times'}
</Button>
