<template>
  <v-form
    ref="form"
    v-model="valid"
    lazy-validation
  >
    <v-text-field
      v-model="name"
      :counter="10"
      :rules="nameRules"
      label="Name"
      required
    ></v-text-field>

    <v-text-field
      v-model="name"
      label="Number of matches"
      required
    ></v-text-field>

   <v-text-field
      v-model="name"
      label="Number of wins"
      required
    ></v-text-field>

    <v-text-field
      v-model="name"
      label="Number of losses"
      required
    ></v-text-field>

    <v-text-field
      v-model="name"
      label="Number of draws"
      required
    ></v-text-field>
    <v-text-field
      v-model="name"
      label="Number of goals scored by team"
      required
    ></v-text-field>
    <v-text-field
      v-model="name"
      label="Number of goals scored against by team"
      required
    ></v-text-field>
    <v-text-field
      v-model="name"
      label="Goal diference"
      required
    ></v-text-field>
    <v-text-field
      v-model="name"
      label="Total Points"
      required
    ></v-text-field>



    <v-btn
      :disabled="!valid"
      color="success"
      class="mr-4"
      @click="validate"
    >
      Accept
    </v-btn>

    <v-btn
      color="error"
      class="mr-4"
      @click="reset"
    >
      Reset Form
    </v-btn>
  </v-form>
</template>
<script>
  export default {
    data: () => ({
   

    methods: {
      validate () {
        this.$refs.form.validate()
      },
      reset () {
        this.$refs.form.reset()
      },

    },
  }
</script>
