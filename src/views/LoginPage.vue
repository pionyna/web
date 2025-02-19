<template>
  <body>
    <aside class="kiri">
      <img src="" />
      <nav>
        <a href="#">Home</a>
        <a href="#">Login</a>
        <a href="#">Peta</a>
      </nav>
    </aside>
    <header>Web Baju Adat</header>
  </body>
</template>

<script></script>

<style>
body {
  display: grid;
  grid-template-areas:
    'header header'
    'aside section'
    'footer footer';
  gap: 0;
  height: 100vh;
  margin: 0;
}
.kiri {
  background-color: #ffd3b6;
  width: 100px;
  height: 700px;
  padding: 20px;
  text-align: center;
}

.kiri img {
  background-color: #a34d3e;
  padding: 20px;
}

.kiri nav a {
  display: block;
  color: #a34d3e;
  text-decoration: none;
  margin: 30px 0;
}

header {
  background-color: #b3e5fc;
  font-family: Arial, Helvetica, sans-serif;
  height: 50px;
  width: 1500px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 30px;
}
</style>
