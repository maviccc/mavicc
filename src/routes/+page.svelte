<script>
  console.log("Portfolio renderingg");
</script>

<svelte:head>
  <title>mavic</title>
  <meta
    name="description"
    content="Hola! Soy Victoria Siempre me ha gustado comunicar y he ido encontrando
        en la expresión gráfica y artística el medio para conectar ideas.
        
        
         La comunicación es el eje. La comunicación como un todo entramado,
        conectado. Las conexiones y relaciones entre las cosas es lo que me
        importa. Pensar como sistema interconectado, mundo de mundos actuando en
        conjunto, simbióticamente."
  />

  <!-- add icon for website -->
  <link rel="icon" type="image/png" href="/website-icon.ico" sizes="16x16" />
</svelte:head>

<section class="container mx-auto px-4 py-8">
  <!-- Header -->
  <header class="text-center mb-12 grid gap-24">
    <div class="flex justify-between">
      <h1 class="text-4xl font-bold mb-4">mavic</h1>
      <div>
        <ul class="flex gap-3 items-center">
          <li>
            <a
              href="https://www.linkedin.com/in/victoria-rodriguez-morales-/"
              rel="noopener noreferrer nofollow"
              target="_blank"
            >
              <img src="/linkedin.png" alt="linkedin" />
            </a>
          </li>

          <li>
            <a
              href="https://www.instagram.com/mavicccc/"
              rel="noopener noreferrer nofollow"
              target="_blank"
              ><img src="/instagram.png" alt="instagram" />
            </a>
          </li>

          <li>
            <a
              href="mailto:victoria.050@hotmail.com"
              rel="noopener noreferrer nofollow"
              target="_blank"
            >
              <img src="/mail.png" alt="mail" /></a
            >
          </li>
        </ul>
      </div>
    </div>
    <div>
      <p class="text-gray-700 text-lg max-w-3xl mx-auto mb-5">
        Hola! Soy Victoria Siempre me ha gustado comunicar y he ido encontrando
        en la expresión gráfica y artística el medio para conectar ideas.
      </p>
      <p class="text-gray-700 text-lg max-w-3xl mx-auto">
        La comunicación es el eje. La comunicación como un todo entramado,
        conectado. Las conexiones y relaciones entre las cosas es lo que me
        importa. Pensar como sistema interconectado, mundo de mundos actuando en
        conjunto, simbióticamente.
      </p>
    </div>
  </header>
</section>

<section class="grid md:grid-cols-[2.121fr_4fr] gap-3 container m-auto">
  <img src="/tazon.jpg" alt="tazon" class="w-full" />
  <img src="/paper.jpg" alt="paper" class="w-full" />
</section>

<style>
  .container {
    max-width: 1200px;
  }
</style>
