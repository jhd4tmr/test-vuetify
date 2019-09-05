<template>
  <div class="name">
    <Test />
    <v-card
      max-width="344"
      class="mx-auto"
    >
      <v-card-title>I'm a title</v-card-title>
      <v-card-text>I'm card text</v-card-text>
      <v-card-actions>
        <!--<v-btn text>Click</v-btn>-->
      </v-card-actions>
    </v-card>
    <VBtn nuxt depressed small :to="`/test`">Joe</VBtn>
    <v-container>
      <v-simple-table>
        <thead>
        <tr>
          <th>name</th>
          <th>age</th>
        </tr>
        </thead>
        <tbody>
        <tr>
          <td>Joe</td>
          <td>18</td>
        </tr>
        <tr>
          <td></td>
          <td>18</td>
        </tr>
        </tbody>
      </v-simple-table>
    </v-container>
  </div>
</template>

<script>
  import Test from '../components/test'
  import {VBtn} from 'vuetify/lib'
  export default {
    components: {
      Test,
      VBtn
    },
    name: "index"
  }
</script>

<style scoped>
  .name {
    background-color: rebeccapurple;
  }
</style>
