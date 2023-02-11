<template>
  <q-layout view="hHh lpR fFf">
    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer bordered class="bg-white text-black q-pa-none">
      <q-btn-group spread>
        <q-btn class="q-pa-md" icon="home" />
        <q-btn class="q-pa-md" icon="search" />
        <q-btn class="q-pa-md" icon="add" />
        <q-btn class="q-pa-md" icon="favorite_border" />
        <q-btn class="q-pa-md" icon="account_circle" />
      </q-btn-group>
    </q-footer>
  </q-layout>
</template>
