<template>
   <v-container
    fill-height
    fluid
    grid-list-xl
  >
       <v-layout >
      <v-flex
        sm6
        xs12
        md8
        lg5
      >
        <material-stats-card
          color="success"
          icon="mdi-school"
          title="Students"
          value="117 "
          small-value="per"
          sub-icon="mdi-account-convert"
          sub-icon-color="success"
          sub-text="Total number of students"
          sub-text-color="text-primary"
        />
      </v-flex>
      
      <v-flex
        sm6
        xs12
        md8
        lg5
      >
        <material-stats-card
          color="info"
          icon="mdi-account-multiple-outline"
          title="Groups"
          value="75"
          sub-icon="mdi-account-multiple-outline"
          sub-icon-color="success"
          sub-text="Total number of groups"
          sub-text-color="text-primary"
        />
      </v-flex>
      <v-flex
        sm6
        xs12
        md8
        lg5
      >
        <material-stats-card
          color="success"
          icon="mdi-account"
          title="Teachers"
          value="24"
          small-value="per"
          sub-icon="mdi-account-convert"
          sub-icon-color="success"
          sub-text="Total number of teachers"
          sub-text-color="text-primary"
        />
      </v-flex>
      <v-flex
        sm6
        xs12
        md8
        lg5
      >
        <material-stats-card
          color="info"
          icon="mdi-book-multiple"
          title="Subjects"
          value="12"
          sub-icon="mdi-book-multiple"
          sub-icon-color="success"
          sub-text="Total number of subjects"
          sub-text-color="text-primary"
        />
      </v-flex>
       </v-layout>
   </v-container>
</template>

<script>
export default {

}
</script>

<style>

</style>
