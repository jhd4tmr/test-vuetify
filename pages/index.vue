<template>
  <v-container>
    <v-btn depressed small>Joe</v-btn>
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
        <td><v-btn depressed small>Joe</v-btn></td>
        <td>18</td>
      </tr>
      </tbody>
    </v-simple-table>
  </v-container>
</template>

<script>
  export default {
    name: "index"
  }
</script>
