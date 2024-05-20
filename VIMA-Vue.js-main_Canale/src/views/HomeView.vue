<template>
  <div class="home-view">
    <center><h1>Bem-vindo à página inicial</h1></center>
    <router-link to="/login">
    <button type="button" class="btn btn-info" id="sair-btn"><span class="material-symbols-outlined">
    directions_run
    </span></button>
    </router-link>
  </div>
</template>

<style scoped>
.btn {
  background-color: rgb(0, 0, 0);
  position: absolute; 
  top: 1vw; 
  right: 1vw;
  height: 40px;
  width: 3vw;
}

.material-symbols-outlined{
  align-items: center;
  justify-content: center;
  position: absolute;
  right: 0.7vw;
  top: 0.5vw;
}
</style>
