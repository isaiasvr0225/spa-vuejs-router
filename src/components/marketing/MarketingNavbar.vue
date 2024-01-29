<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header class="sticky-top">
    <nav class="d-flex justify-content-around navbar navbar-expand-sm bg-primary navbar-dark">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
        <li class="nav-item">
          <Router-Link class="nav-link" to="/consultoring">About us</Router-Link>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input
          class="form-control me-2"
          type="search"
          placeholder="¿Qué deseas comprar?"
          aria-label="Search"
        />
        <button class="rounded-md self-center bg-violet-500 font-bold px-6 py-2 text-sm text-white shadow-sm hover:bg-violet-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600" type="submit">Buscar</button>
      </form>
      <a class="navbar-brand" href="#">CodeXpert Marketing</a>
    </nav>
  </header>
</template>

<style scoped>
  form{
    right: 200px;
    width: 600px;
  }

  a{
    margin-left: 10px;
  }
</style>
