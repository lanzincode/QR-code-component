<script>
  export let image;
  export let alt;
  export let title;
  export let description;
</script>

<article class="card">
  <figure>
    <img src={image} {alt} />
    <figcaption>
      <h1>{title}</h1>
      <p>{description}</p>
    </figcaption>
  </figure>
</article>
