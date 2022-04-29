<script>
  import Hero from '../components/Hero.svelte'
  import Featured from '../components/Products/Featured.svelte'
  import { link } from 'svelte-routing'

  // function getProps() {
  //   return { class: 'btn btn-primary btn-hero' }
  // }
</script>

<Hero>
  <a href="/products" class="btn btn-primary btn-hero" use:link>shop now</a>
</Hero>
<Featured title="featured products" />
