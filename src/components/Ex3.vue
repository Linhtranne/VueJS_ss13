<template>
    <div>
        <h1>Bài 3</h1>
        <v-card
        class="mx-auto"
        color="surface-variant"
        image="https://cdn.vuetifyjs.com/docs/images/cards/dark-beach.jpg"
        max-width="340"
        subtitle="Whitehaven beach"
        title="Top 10 Australian beach"
      >
        <template v-slot:actions>
          <v-btn
            append-icon="mdi-chevron-right"
            color="red-lighten-2"
            text="Share"
            variant="outlined"
  
          ></v-btn>
          <v-btn
          append-icon="mdi-chevron-left"
          color="red-lighten-2"
          text="Explore"
          variant="outlined"
        ></v-btn>
        </template>
        
      </v-card>
    </div>
  </template>