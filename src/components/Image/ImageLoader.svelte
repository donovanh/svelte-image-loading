<script>
  export let src
  export let alt
  export let className = ''

  import Image from './Image.svelte'
  import IntersectionObserver from './IntersectionObserver.svelte'
  
</script>

<IntersectionObserver once={true} top={80} let:intersecting={intersecting}>
  {#if intersecting}
    <Image {alt} {src} {className} {intersecting} />
  {/if}
</IntersectionObserver> 
