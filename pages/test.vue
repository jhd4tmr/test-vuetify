<template>
  <VContainer>
    <VBtn depressed small>Joe</VBtn>
    <VSimpleTable>
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
        <td><VBtn depressed small>Joe</VBtn></td>
        <td>18</td>
      </tr>
      </tbody>
    </VSimpleTable>
  </VContainer>
</template>

<script>
  import {VContainer, VSimpleTable, VBtn} from 'vuetify/lib'
  export default {
    components: {
      VContainer,
      VSimpleTable,
      VBtn
    },
    name: "test"
  }
</script>
