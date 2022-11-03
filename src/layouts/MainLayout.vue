<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title> Quasar App </q-toolbar-title>

        <div>
          Quasar v{{ $q.version }}
          <q-btn to="/blank" flat dense round icon="link" aria-label="Link" />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import { useRouter } from "vue-router";

export default {
  name: "MainLayout"
};
</script>
