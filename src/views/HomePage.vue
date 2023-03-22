<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <div id="container"
        class="w-screen h-screen py-[10vw] px-[10vh] text-center flex flex-col items-center justify-between">
        <div>
          <div class="text-[10vw] font-black">Дата</div>
          <div class="dates w-screen flex flex-row font-bold text-[20vw] overflow-x-scroll">
            <span class="dateItem">1</span>
            <span class="dateItem">2</span>
            <span class="dateItem">3</span>
            <span class="dateItem">4</span>
            <span class="dateItem">5</span>
            <span class="dateItem">6</span>
            <span class="dateItem">7</span>
            <span class="dateItem">8</span>
            <span class="dateItem">9</span>
            <span class="dateItem">10</span>
          </div>
          <div class="text-[5vw] font-black">Марта</div>
        </div>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
</script>

<style scoped>
.dateItem {
  margin-left: 1vh;
  margin-right: 1vh;
}

.dates::-webkit-scrollbar {
  display: none;
}
</style>
