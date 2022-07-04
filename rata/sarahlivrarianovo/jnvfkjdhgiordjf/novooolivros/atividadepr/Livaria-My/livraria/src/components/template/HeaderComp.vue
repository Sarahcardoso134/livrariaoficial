<template>
  <header>
    <div>
      <span> <RouterLink to="/editoras">Editoras</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/categorias">Categorias</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/autores">Autores</RouterLink> </span>
      <span>|</span>
      <span> <RouterLink to="/livros">Livros</RouterLink> </span>
    </div>
    <div>
      <span> <RouterLink to="/login">Login</RouterLink> </span>
    </div>
  </header>
</template>

<style>
header span {
  padding: 0 20px;
}

header {
  background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSaViVx1n1mNlI8aFPoXnlVy3KZDoBe1NLf5Q&usqp=CAU);
  background-color: #000000;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: #ffffff;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
