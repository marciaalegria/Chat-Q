<template>
    <q-page padding>
      <div class="q-pa-md row justify-center">
        <div style="width: 100%; max-width: 400px">
          <q-chat-message :text="['hey, vas a la entrevista?']" sent name="me" />
          <q-chat-message :text="['sí, deséame éxito?']" name="JuanCri" />
        </div>
      </div>
    </q-page>
  </template>
  
  <script setup></script>