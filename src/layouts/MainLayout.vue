<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="header">
      <q-toolbar class="header-toolbar q-pt-md">
        
        <q-toolbar-title>
          <div class="logo">
              <img src="../assets/image/logo.png" alt="logo">
          </div>
        </q-toolbar-title>

        <q-tabs class="q-text-capitalize menu-bar" v-model="tab">
          <q-tab name="inicio" label="Início" />
          <q-tab name="autorais" label="Autorais" />
          <q-tab name= "ensaio" label="Ensaio Fotografico" />
          <q-tab name="sobre" label="Sobre Felex" />
        </q-tabs>

      </q-toolbar>

    </q-header>

      <q-card class="q-text-white my-card" style="width: 550px" flat>
        <q-card-section>
          <div>
            <h4> Felix Bonix Bonix Ivanildo </h4>
            <p class="text-body1"> Agencia de fotografias profissional, estamos situados na cidade de Nacala Porto</p>
            <p class="text-body1"> O ferecemos serviços de fotografia e filmagem de imegens de alta qualidade </p>

            <q-btn class="q-mt-lg" color="grey-9" text-color="red-1" glossy unelevated icon="camera_enhance" label="Marque a sua seção " />
          </div>
        </q-card-section>
      </q-card>

    <q-footer elevated>
        <q-toolbar>
          <q-toolbar-title>Footer</q-toolbar-title>
        </q-toolbar>
    </q-footer>

  </q-layout>
</template>

<script>
import { defineComponent, ref } from 'vue'

const linksList = [
  {
    title: 'Docs',
    caption: 'quasar.dev',
    icon: 'school',
    link: 'https://quasar.dev'
  },
  {
    title: 'Github',
    caption: 'github.com/quasarframework',
    icon: 'code',
    link: 'https://github.com/quasarframework'
  },
  {
    title: 'Discord Chat Channel',
    caption: 'chat.quasar.dev',
    icon: 'chat',
    link: 'https://chat.quasar.dev'
  },
  {
    title: 'Forum',
    caption: 'forum.quasar.dev',
    icon: 'record_voice_over',
    link: 'https://forum.quasar.dev'
  },
  {
    title: 'Twitter',
    caption: '@quasarframework',
    icon: 'rss_feed',
    link: 'https://twitter.quasar.dev'
  },
  {
    title: 'Facebook',
    caption: '@QuasarFramework',
    icon: 'public',
    link: 'https://facebook.quasar.dev'
  },
  {
    title: 'Quasar Awesome',
    caption: 'Community Quasar projects',
    icon: 'favorite',
    link: 'https://awesome.quasar.dev'
  }
]

export default defineComponent({
  name: 'MainLayout',

  setup () {
    const leftDrawerOpen = ref(false)

    return {
      
    }
  }
})
</script>
