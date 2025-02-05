<template>
  <div class="min-h-screen bg-background text-primary">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
  // Aucun import spécifique nécessaire ici
</script>

<style>
/* Déclaration globale de la police depuis public/fonts */
@font-face {
  font-family: 'MaPolice';
  src: url('/fonts/esse-grotesk.otf') format('otf');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

/* Application de la police sur le body */
body {
  font-family: 'MaPolice', sans-serif;
}
</style>
