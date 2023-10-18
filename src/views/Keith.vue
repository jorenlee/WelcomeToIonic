<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Keith</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      
<ion-searchbar></ion-searchbar>
     <ion-thumbnail>
    <img alt="Silhouette of mountains" src="https://media.npr.org/assets/img/2017/09/12/macaca_nigra_self-portrait-3e0070aa19a7fe36e802253048411a38f14a79f8-s1100-c50.jpg" />
  </ion-thumbnail>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>


<style>
  ion-thumbnail {
    --size: 100%;
    --border-radius: 14px;
  }
</style>
