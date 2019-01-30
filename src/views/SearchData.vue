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
        md4
        
      >
      
       <v-text-field
            solo
            placeholder="Search data"
            clearable
            append-icon="mdi-magnify"
          ></v-text-field>
 <v-divider></v-divider>
    </v-flex>
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
