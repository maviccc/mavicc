<script>
  console.log("Portfolio rendering");
</script>

<svelte:head>
  <title>Portfolio - Mavic</title>
  <meta name="description" content="Landing portfolio for Mavic" />
</svelte:head>

<section class="container mx-auto px-4 py-8">
  <!-- Header -->
  <header class="text-center mb-12">
    <h1 class="text-4xl font-bold mb-4">Mavic</h1>
    <p class="text-gray-700 text-lg max-w-3xl mx-auto">
      Hola! Soy Victoria. Siempre me ha gustado comunicar y he ido encontrando
      en la expresión gráfica y artística el medio para conectar ideas.
    </p>
  </header>

  <!-- Project Sections -->
  <section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
    <!-- Project 1 -->
    <div class="flex flex-col">
      <p class="text-sm text-gray-600 text-center">
        La identidad se construye incentivando nuestra creatividad.
      </p>
    </div>
    <!-- Project 2 -->
    <div></div>
  </section>

  <!-- Project Title Section -->
  <section class="text-center mb-12">
    <h2 class="text-2xl font-bold">Vaivén test</h2>
    <p class="text-gray-600 text-sm">Diseño de estampas a partir de collage</p>
  </section>

  <!-- More Projects -->
  <section class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- Collage Fabric -->
  </section>

  <!-- Footer Project -->
  <section class="mt-12 text-center">
    <h2 class="text-2xl font-bold">Marea</h2>
  </section>
</section>

<style>
  .container {
    max-width: 1200px;
  }
</style>
