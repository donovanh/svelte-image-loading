<script>
  import ImageLoader from './components/Image/ImageLoader.svelte';

  // Generate random number to stop the images caching
  function rand(min, max) {
    let randomNum = Math.random() * (max - min) + min;
    return Math.round(randomNum);
  }

</script>

<style>
  li {
    list-style: none;
    background: #eee;
    width: 200px;
    height: 200px;
    margin: 2em;
  }
</style>

<h2>Image loading demo</h2>

<p>Scroll to see images fade-in</p>

<ul>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
  <li><ImageLoader src={`https://picsum.photos/seed/${rand(0,200)}/800/800`} alt="Example image"></ImageLoader></li>
</ul>