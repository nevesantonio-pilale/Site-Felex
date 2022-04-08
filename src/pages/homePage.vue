<template>
  <q-page class="container">
    <div>
        <q-card class="q-text-white my-card" style="width: 550px" flat>
        <q-card-section>
          <div>
            <h4> Felix Bonix Bonix Ivanildo </h4>
            <p class="text-body1"> Agencia de fotografias profissional, estamos situados na cidade de Nacala Porto</p>
            <p class="text-body1"> O ferecemos serviços de fotografia e filmagem de imegens de alta qualidade </p>

            <q-btn
              clickable
              class="q-mt-lg"
              color="grey-9"
              text-color="red-1"
              glossy
              unelevated
              icon="camera_enhance"
              label="Marque a sua seção " />
          </div>
        </q-card-section>
      </q-card>

    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'homePage'
})
</script>
