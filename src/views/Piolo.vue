<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Piolo ToolBar</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Piolo</ion-title>
        </ion-toolbar>
      </ion-header>

              <ion-thumbnail>
    <img alt="Silhouette of mountains" src="https://pbs.twimg.com/profile_images/454972291383050240/ZmV9Xk6s_400x400.jpeg" />
  </ion-thumbnail>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
