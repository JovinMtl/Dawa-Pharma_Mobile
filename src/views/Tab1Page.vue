<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 1s</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <div class="page1Container" style="width: 100%; height: 100%;">
         <div class="content1" style="background-color: greenyellow; width: 100%; height: 4px">
          <div class="element1"></div>
         </div>
         <div class="content2" style="background-color: grey; width: 100%; height: 98%;">
          <div class="element1" style="background-color: seashell; width: 100%; height: 20px">
            <div class="elem1"></div>
          </div>
         </div>
         <div class="content3" style="background-color: greenyellow; width: 100%; height: 4px"></div>
      </div>
      
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>

<style scoped>

</style>