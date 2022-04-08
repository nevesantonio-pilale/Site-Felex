<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="header">
      <q-toolbar class="header-toolbar q-pt-md">

        <q-toolbar-title>
          <div class="logo">
              <img src="../assets/image/logo.png" alt="logo">
          </div>
        </q-toolbar-title>

        <q-tabs class="menu-bar" v-model="tab">
          <q-tab class="tab-list text-capitalize" name="inicio" label="Início" />
          <q-tab class="tab-list text-capitalize" name="autorais" label="Sobre Felex" />
          <q-tab class="tab-list text-capitalize" name= "ensaio" label="Ensaio Fotografico" />
          <q-tab class="tab-list text-capitalize" name="sobre" label="contacto" />
        </q-tabs>

      </q-toolbar>

    </q-header>

    <q-footer elevated>
        <q-toolbar>
          <q-toolbar-title>Footer</q-toolbar-title>
        </q-toolbar>
    </q-footer>

    <q-page-container>
      <router-view />
    </q-page-container>

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
