<script>
  let { image, title, description } = $props();
</script>

<main>
  <section class="card">
    <img src={image} alt="QR Code" />
    <h1>{title}</h1>
    <p>{description}</p>
  </section>
</main>
