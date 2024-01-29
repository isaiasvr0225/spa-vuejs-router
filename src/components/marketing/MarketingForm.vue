<template>
  <hr class="mt-6" />
  <h2 class="bg-sky-500 text-white text-center text-2xl rounded-lg font-bold">
    ¿Quieres que tu producto tu producto esté en nuestro Marketplace?
    ¡Contactanos llenando el siguiente formulario!
  </h2>
  <div class="container mt-8 mb-8 border border-solid rounded-lg" id="form-container">
    <h3 class="mt-3">Formulario de contacto</h3>
    <p class="mt-4 mb-4">
      Por favor, complete el siguiente formulario para ponernos en contacto
      contigo:
    </p>
    <hr />
    <form class="mt-3" action="http://localhost:8080/clientes" method="post">
      <div class="mb-3">
        <label for="nombre" class="form-label"><b>Nombre:</b></label>
        <input
          type="text"
          class="form-control"
          placeholder="Ingrese su nombre"
          name="nombre"
          required
        />
      </div>

      <div class="mb-3">
        <label for="apellidos" class="form-label"><b>Apellidos:</b></label>
        <input
          type="text"
          class="form-control"
          placeholder="Ingrese sus apellidos"
          name="apellidos"
          required
        />
      </div>

      <div class="mb-3">
        <label for="email" class="form-label"><b>Email:</b></label>
        <input
          type="text"
          class="form-control"
          placeholder="Ingrese su email"
          name="email"
          required
        />
      </div>

      <div class="mb-3">
        <label for="telefono" class="form-label"><b>Teléfono:</b></label>
        <input
          type="text"
          class="form-control"
          placeholder="Ingrese su teléfono"
          name="telefono"
          required
        />
      </div>

      <div class="mb-3">
        <label for="pais" class="form-label"><b>País:</b></label>
        <select name="pais">
          <option>--Selecciona--</option>
          <option value="Colombia">Colombia</option>
          <option value="Argentina">Argentina</option>
          <option value="Brasil">Brasil</option>
          <option value="Chile">Chile</option>
          <option value="México">México</option>
        </select>
      </div>

      <button
        type="submit"
        class="ml-auto rounded-md mb-4 bg-violet-500 font-bold px-6 py-2 text-sm text-white shadow-sm hover:bg-violet-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
      >
        Enviar
      </button>
    </form>
  </div>
</template>

<style scoped>
#form-container {
  width: 500px;
}

h3 {
  font-family: "Roboto", sans-serif;
  font-size: 40px;
  color: black;
}

h2 {
  padding-top: 30px;
  height: 100px;
}
</style>
