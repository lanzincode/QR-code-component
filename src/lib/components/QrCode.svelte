<script>
  let { image, alt, title, description } = $props();
</script>

<main>
  <section class="card">
    <img src={image} {alt} />
    <h1>{title}</h1>
    <p>{description}</p>
  </section>
</main>
