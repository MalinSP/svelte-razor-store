<script>
  import Hero from '../components/Hero.svelte'
  import { link } from 'svelte-routing'

  // function getProps() {
  //   return { class: 'btn btn-primary btn-hero' }
  // }
</script>

<Hero>
  <a href="/products" class="btn btn-primary btn-hero" use:link>shop now</a>
</Hero>
