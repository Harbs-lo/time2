<template>
  <header>
    <div class="menu-esquerdo">
      <span><RouterLink to="/">Home</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/jogadores">Jogadores</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/times">Times</RouterLink></span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
</template>
<style>
  header{background-color: rgb(0, 114, 28);
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 2%;
  justify-content: space-between;
  }
</style>