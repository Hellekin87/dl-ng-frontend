<template>
  <v-container
    fill-height
    fluid
    grid-list-xl
  >
    <v-layout
      justify-start
      wrap
    >

      <v-flex
        md12
      >

        <material-card
        class="text--darken-3"
          color="conti-orange"
          flat
          full-width
          title="Table on Plain Background"
          text="Here is a subtitle for this table"
        >


  <!-- <v-stepper vertical>
    <v-stepper-step step="1">
      Create a dataset
      <small>fill out the form</small>
    </v-stepper-step>

    <v-stepper-content step="1">
      <v-card color="grey lighten-1" class="mb-5" height="200px"></v-card>
      <v-btn color="primary">Continue</v-btn>
    </v-stepper-content>

    <v-stepper-step step="2">Add Data</v-stepper-step>

    <v-stepper-step step="3">Analytics</v-stepper-step>
  </v-stepper> -->

  <v-stepper style="margin-bottom: 20px;">
      <v-stepper-header>
        <v-stepper-step color="blue" step="1">Create dataset</v-stepper-step>

        <v-divider></v-divider>

        <v-stepper-step step="2">Add data</v-stepper-step>

        <v-divider></v-divider>

        <v-stepper-step step="3">Analytics</v-stepper-step>
      </v-stepper-header>
    </v-stepper>



     <v-text-field
     clearable
         class="purple-input"           
     label="User Name"
    />





         
        </material-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    
  })
}
</script>
