<template>
  <q-page padding>
    <!-- content -->
    <h2>Provjera ishoda 2</h2>
    <q-card>
      <q-card-section>
        <q-input v-model="ime" label="Unesi ime" />
      </q-card-section>
      <q-btn @click="posalji()">Pošalji</q-btn>
      <!--q-card-section>
        {{ ispis }}
      </q-card-section-->
    </q-card>
  </q-page>
</template>

<script setup>

</script>
