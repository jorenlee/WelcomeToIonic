<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>George</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">George</ion-title>
        </ion-toolbar>
      </ion-header>

         <ion-thumbnail>
    <img alt="Silhouette of mountains" src="https://news.wttw.com/sites/default/files/styles/full/public/field/image/KindaGiraffeBrookfield.jpg?itok=TBqKk0aN" />
  </ion-thumbnail>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
import AnotherComponent from '@/components/AnotherComponent.vue';
</script>
