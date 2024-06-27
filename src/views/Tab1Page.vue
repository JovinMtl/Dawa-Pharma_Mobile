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
         <div class="content2" style="background-color: grey; width: 100%; height: 98%; font-weight: 700;">
          <div class="element1" style="display: flex;width: 100%; height: 25px">
            <div class="elem1" style="width: 30%; height: 100%; border: 1px solid black; color: #000;">
              Médicament
            </div>
            <div class="elem2" style="width: 10%; height: 100%; border: 1px solid black; color: #000;">
              Qte
            </div>
            <div class="elem3" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
              Px.A
            </div>
            <div class="elem4" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
              Px.V
            </div>
            <div class="elem5" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
              Bénéf
            </div>
          </div>

          <div class="element2" style="background-color: white; width: 100%; height: 91%; color: #000;">
            <div class="element1" style="display: flex;width: 100%; height: 25px">
              <div class="elem1" style="width: 30%; height: 100%; border: 1px solid black; color: #000;">
                Médicament
              </div>
              <div class="elem2" style="width: 10%; height: 100%; border: 1px solid black; color: #000;">
                Qte
              </div>
              <div class="elem3" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Px.A
              </div>
              <div class="elem4" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Px.V
              </div>
              <div class="elem5" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Bénéf
              </div>
            </div>
          </div>

          <div class="element2" style="width: 100%; height: 5%; color: #000;">
            <div class="element1" style="display: flex;width: 100%; height: 25px; text-align: right;">
              <div class="elem1" style="width: 30%; height: 100%; border: 1px solid black; color: #000;">
                Total
              </div>
              <div class="elem2" style="width: 10%; height: 100%; border: 1px solid black; color: #000;">
                Qte
              </div>
              <div class="elem3" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Px.A
              </div>
              <div class="elem4" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Px.V
              </div>
              <div class="elem5" style="width: 20%; height: 100%; border: 1px solid black; color: #000;">
                Bénéf
              </div>
            </div>
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