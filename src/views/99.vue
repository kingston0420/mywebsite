<template>
  <div class="99">
    <h1>This is an 99 page</h1>
      <table>
      <tr>
        <th v-for = "j in [''].concat(list2)" :key="j">
          {{ j }}
        </th>
      </tr>
      <tr v-for = "i in list" :key="i">
        <th>{{ i }}</th>
        <td v-for = "j in list2" :key="j">
          {{i * j}}
        </td>
      </tr>
    </table>
  </div>
</template>

<script>      
  export default {
 name: '99',
 data ()  {
  return {
    list: [1,2,3,4,5,6,7,8,9],
    list2: [1,2,3,4,5,6,7,8,9]
    }
  }
 }
</script>

<style scoped>
  table, th, td {
    border: 1px solid black;
    padding: 0.2em;
  }

  table {
    border-collapse: collapse;
    margin: 0 auto;
  }
</style>

