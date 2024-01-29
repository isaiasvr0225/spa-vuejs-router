<template>
  <main class="flex justify-center">
    <div class="flex flex-col justify-evenly mt-32">
      <h2>¡Lleva tu negocio a otro nivel!</h2>
      <p class="text-slate-600">
        Nuestros sistemas son fáciles de usar, seguros, escalables, lo que lo
        hace perfecto para empresas de todos los tamaños. Con
        <span class="font-bold">CodeXpert</span>, tu idea de negocio puede
        escalar a un nivel mayor.
      </p>
      <a
        class="rounded-md self-center mt-20 bg-cyan-500 px-3 py-2 text-sm font-semibold text-white shadow-xl hover:bg-cyan-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
        href="#form"
        >Contactanos</a
      >
    </div>
  </main>

  <img class="z-0" id="wave-separator" src="wave.png" alt="wave separator" />

  <section class="mt-20">
    <div class="flex flex-row justify-center" id="titulo-clientes">
      <h3 class="font-sans text-black text-4xl font-bold">CLIENTES</h3>
    </div>
    <div class="grid grid-cols-3 gap-4 mb-6 ml-32">
      <article>
        <img src="BOGOTA-LOGO.png" alt="" />
      </article>
      <article>
        <img src="CAF-LOGO.png" alt="" />
      </article>
      <article>
        <img src="CROPPED.png" alt="" />
      </article>
      <article>
        <img src="MINERIA-LOGO.png" alt="" />
      </article>
      <article>
        <img src="PASWORD-LOGO.png" alt="" />
      </article>
      <article>
        <img src="u-nacional.png" alt="" />
      </article>
    </div>
  </section>
</template>

<style scoped>
main {
  background-image: url("fondo.png");
  height: 620px;
}

div {
  height: 400px;
}

h2 {
  width: 700px;
  font-family: "Inter", sans-serif;
  text-align: center;
  font-size: 80px;
  color: black;
  line-height: 70px;
  vertical-align: baseline;
  letter-spacing: -1.5px;
  word-spacing: 0px;
}
p {
  width: 780px;
  font-family: "Roboto Condensed", sans-serif;
  font-size: 20px;
  text-align: center;
}

button {
  width: 100px;
  height: 40px;
}

#wave-separator {
  width: 2000px;
  filter: hue-rotate(334deg) saturate(100%);
}

#titulo-clientes {
  height: 60px;
}
</style>
