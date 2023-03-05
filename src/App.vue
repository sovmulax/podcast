<script setup>
import Player from './components/Player.vue';
</script>

<template>
  <header>
    <img alt="Vue logo" src="./assets/white.png" width="143" height="40" />
    <div class="menu">
      <span>Introduction</span>
      <span>Podcast</span>
      <span>Intervenants</span>
      <span>Membres</span>
    </div>
  </header>
  <div class="intro">
    <h1>Introduction</h1>
    <br />
    <p>
      Bienvenue à notre podcast sur le modèle économique de Github. Dans cet épisode, nous
      allons explorer les différentes facettes du modèle économique de Github qui a permis
      à la plateforme de croître rapidement et devenir l'un des leaders de l'industrie du
      développement de logiciels. <br /><br />
      Github est un service d'hébergement web de code source pour les projets de
      développement de logiciels. Dans ce podcast, nous allons discuter des différentes
      sources de revenus de Github, notamment la vente de plans d'abonnement, les services
      professionnels et les intégrations tierces. Nous allons également explorer comment
      Github a réussi à construire une communauté de développeurs passionnés et engagés
      qui ont contribué à la croissance de la plateforme. <br /><br />
      Restez à l'écoute pour en savoir plus sur le modèle économique de Github et comment
      il a permis à la plateforme de devenir l'un des acteurs les plus influents de
      l'industrie du développement de logiciels.
    </p>
  </div>

  <div class="podcast">
    <h1>Podcast</h1>
    <div>
      <br />
      <br />
      <img alt="Vue logo" src="./assets/cover.png" /><br>

    </div>
  </div>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  margin-top: 1rem;
  padding: 1rem 3rem 1rem 3rem;
  width: 100%;
}

.menu {
  width: 30%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.intro {
  padding: 5rem 10rem 0 10rem;
  color: #181818;
}

.intro > h1 {
  text-align: center;
}

.intro > p {
  text-align: justify;
}

.podcast {
  width: 100%;
  color: #181818;
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.podcast > h1 {
  text-align: center;
}

.podcast > div > img {
  width: 50%;
}

span,
h1 {
  color: #181818;
}
</style>
