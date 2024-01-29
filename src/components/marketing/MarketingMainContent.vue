<script setup>
import ProductCard from "./ProductCard.vue";
</script>
<template>
  <main>
    <section>
      <div
        id="carouselExampleAutoplaying"
        class="carousel slide"
        data-bs-ride="carousel"
      >
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://m.media-amazon.com/images/I/71c4Hv6TyFL._SX3000_.jpg" class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="https://m.media-amazon.com/images/I/61tX6L542kL._SX3000_.jpg" class="d-block w-100" alt="..." />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExampleAutoplaying"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExampleAutoplaying"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </section>

    <h2>Articulos más buscados</h2>
    <section class="row mt-3 ml-4">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>

    <h2>Computadores</h2>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
    <h2>Consolas y Videojuegos</h2>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
    <h2>Celulares</h2>
    <section class="row mt-4 ml-3">
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_825580-MCO53019567085_122022-O.webp"
          productTitle="Equipo De Sonido Teatro En Casa Minicomponente"
          productOwnerName="World Sound"
          productPrice="550.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_901305-MLU54981633846_042023-O.webp"
          productTitle="Portatil Hp 15-ef2522la Amd Ryzen 3 5300u 8gb"
          productOwnerName="Alejandro Perez"
          productPrice="1.400.000"
        />
      </article>
      <article class="col">
        <ProductCard
          productImageUrl="https://http2.mlstatic.com/D_NQ_NP_618548-MLA44156593642_112020-O.webp"
          productTitle="Samsung A30 64gb Negro 4 Gb Ram"
          productOwnerName="Mundo Cell"
          productPrice="379.905"
        />
      </article>
    </section>
  </main>
</template>

<style scoped>
section {
  width: 100%;
  margin: 0;
  padding: 0;

}

img {
  width: 100%;
  height: 500px;
}

article {
  margin: 0;
}

h2{
  font-size: x-large;
  color: black;
  font-weight: bold;
  margin-top: 20px;
  padding-left: 30px;
}
</style>
