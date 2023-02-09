<template>
  <q-layout view="hHh lpR fFf">
    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer bordered class="bg-white text-black">
      <q-toolbar class="q-pa-none">
        <q-toolbar-title class="q-pa-none">
          <q-tabs
            active-color="primary"
            indicator-color="white"
            align="justify"
          >
            <q-tab name="innerMails" icon="home" />
            <q-tab name="innerAlarms" icon="search" />
            <q-tab size="lg" name="innerMovies" icon="search" />
            <q-tab name="s" icon="favorite_border" />
            <q-tab name="d" icon="account_circle" />
          </q-tabs>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>
