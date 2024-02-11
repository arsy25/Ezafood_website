<template>
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css"
  />
  <q-page class="q-pa-md bg-green">
    <ul class="background">
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
    <q-img class="logo"></q-img>

    <div class="row q-gutter-md">
      <q-card class="cardcuy" flat bordered>
        <q-img src="/image/nasigoreng.jpeg" />

        <q-card-section>
          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-blue">
              Nasi Goreng Excellento
            </div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="correct" />
              Halal
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="text-subtitle1 text-white">Rp. 10.000</div>
          <div class="text-caption text-grey">
            Nasi goreng spesial dengan cita rasa yang menggugah selera
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions>
          <q-btn
            color="primary"
            class="q-pa-md"
            rounded
            href="https://wa.link/cv2otq"
          >
            <i class="bi bi-whatsapp text-white text-h6 q-mr-sm"></i>Pesan
            Sekarang
          </q-btn>
        </q-card-actions>
      </q-card>

      <q-card class="cardcuy" flat bordered>
        <q-img src="/image/esjeruk.jpeg" />

        <q-card-section>
          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-blue">Es Jeruk Peras</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="correct" />
              Halal
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="text-subtitle1 text-white">Rp. 5.000</div>
          <div class="text-caption text-grey">
            Es jeruk yang sangat segar di setiap saat, segar nikmat dan cocok
            untuk diminum di cuaca panas
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions>
          <q-btn
            color="primary"
            class="q-pa-md"
            rounded
            href="https://wa.link/fui2vo"
          >
            <i class="bi bi-whatsapp text-white text-h6 q-mr-sm"></i>Pesan
            Sekarang
          </q-btn>
        </q-card-actions>
      </q-card>

      <q-card class="cardcuy" flat bordered>
        <q-img src="/image/rbk.jpeg" />

        <q-card-section>
          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-blue">Roti Bakar Bleber</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="correct" />
              Halal
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="text-subtitle1 text-white">Rp. 8.000</div>
          <div class="text-caption text-grey">
            Roti bakar dengan aneka kenikmatan yang meleleh, cocok dihidangkan
            dengan Es Teh NengNai
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions>
          <q-btn
            color="primary"
            class="q-pa-md"
            rounded
            href="https://wa.link/3o9366"
          >
            <i class="bi bi-whatsapp text-white text-h6 q-mr-sm"></i>Pesan
            Sekarang
          </q-btn>
        </q-card-actions>
      </q-card>

      <q-card class="cardcuy" flat bordered>
        <q-img src="/image/mo.jpeg" />

        <q-card-section>
          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-blue">Mochi Durian</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="correct" />
              Halal
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="text-subtitle1 text-white">Rp. 6.000</div>
          <div class="text-caption text-grey">
            Mochi seperti umumnya, enak, kenyal, sehat, cocok untuk cuaca panas
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions>
          <q-btn
            color="primary"
            class="q-pa-md"
            rounded
            href="https://wa.link/9c1of7"
          >
            <i class="bi bi-whatsapp text-white text-h6 q-mr-sm"></i>Pesan
            Sekarang
          </q-btn>
        </q-card-actions>
      </q-card>

      <q-card class="cardcuy futer" flat bordered>
        <q-img src="/image/teh.jpeg" />

        <q-card-section>
          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-blue">Es Teh NengNai</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="correct" />
              Halal
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="text-subtitle1 text-white">Rp. 5.000</div>
          <div class="text-caption text-grey">
            Es teh manis yang cocok diminum saat puasa, tapi pas berbuka
            minumnya
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions>
          <q-btn
            color="primary"
            class="q-pa-md"
            rounded
            href="https://wa.link/js9p1y"
          >
            <i class="bi bi-whatsapp text-white text-h6 q-mr-sm"></i>Pesan
            Sekarang
          </q-btn>
        </q-card-actions>
      </q-card>
    </div>
    <q-footer reveal class="q-mt-xl">
      <q-toolbar>
        <q-toolbar-title class="text-center futer2"
          >SELAMAT BERBELANJA</q-toolbar-title
        >
      </q-toolbar>
    </q-footer>
  </q-page>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      stars: ref(4),
    };
  },
};
</script>

<style>
.logo {
  background-image: url("/image/ezafoosd.png");
  background-repeat: no-repeat;
  background-size: 60%;
  margin-top: -10%;
  margin-bottom: -25%;
  margin-left: -3%;
}
.futer {
  margin-bottom: 20%;
}

.futer2 {
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  font-weight: 900;
}

.cardcuy {
  background: transparent;
  backdrop-filter: blur(10px);
  border: 1px rgb(255, 255, 255) solid;
  border-radius: 20px;
}
@keyframes cube {
  from {
    transform: scale(0) rotate(0deg) translate(-50%, -50%);
    opacity: 1;
  }
  to {
    transform: scale(20) rotate(960deg) translate(-50%, -50%);
    opacity: 0;
  }
}

@keyframes cube {
  from {
    transform: scale(0) rotate(0deg) translate(-50%, -50%);
    opacity: 1;
  }
  to {
    transform: scale(20) rotate(960deg) translate(-50%, -50%);
    opacity: 0;
  }
}

.background {
  position: fixed;
  width: 100vw;
  height: 100vh;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  background: #101b33;
  overflow: hidden;
}
.background li {
  position: absolute;
  top: 80vh;
  left: 45vw;
  width: 10px;
  height: 10px;
  border: solid 1px #0e182d;
  color: transparent;
  transform-origin: top left;
  transform: scale(0) rotate(0deg) translate(-50%, -50%);
  animation: cube 11s ease-in forwards infinite;
}
undefined .background li:nth-child(0) {
  animation-delay: 0s;
  left: 23vw;
  top: 14vh;
}

.background li:nth-child(1) {
  animation-delay: 2s;
  left: 5vw;
  top: 72vh;
  border-color: #ffffff;
}

.background li:nth-child(2) {
  animation-delay: 4s;
  left: 60vw;
  top: 22vh;
  border-color: #ffffff;
}

.background li:nth-child(3) {
  animation-delay: 6s;
  left: 13vw;
  top: 55vh;
  border-color: #ffffff;
}

.background li:nth-child(4) {
  animation-delay: 8s;
  left: 34vw;
  top: 33vh;
  border-color: #ffffff;
}

.background li:nth-child(5) {
  animation-delay: 10s;
  left: 89vw;
  top: 23vh;
  border-color: #ffffff;
}

.background li:nth-child(6) {
  animation-delay: 12s;
  left: 44vw;
  top: 79vh;
  border-color: #ffffff;
}

.background li:nth-child(7) {
  animation-delay: 14s;
  left: 79vw;
  top: 46vh;
  border-color: #ffffff;
}

.background li:nth-child(8) {
  animation-delay: 16s;
  left: 64vw;
  top: 0vh;
}

.background li:nth-child(9) {
  animation-delay: 18s;
  left: 71vw;
  top: 95vh;
}

.background li:nth-child(10) {
  animation-delay: 20s;
  left: 47vw;
  top: 91vh;
  border-color: #ffffff;
}

.background li:nth-child(11) {
  animation-delay: 22s;
  left: 18vw;
  top: 44vh;
  border-color: #ffffff;
}

.background li:nth-child(12) {
  animation-delay: 24s;
  left: 94vw;
  top: 62vh;
}
</style>
