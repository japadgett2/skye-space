<template>
  <div class="about">
    <h1>Bank of Mr. Dad</h1>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>


<script>
  export default {
    data() {
      return {
        items: [
          { date: '06/15/2021', credit: 0, debit: 0, total: 0.00 },
          { date: '06/16/2021', credit: 12, debit: 0, total: 12.00 },
          { date: '07/02/2021', credit: 0.60, debit: 0, total: 12.60 },
        ]
      }
    }
  }
</script>