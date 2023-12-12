<template>
  <Header/>
  <Balance/>
  <IncomeExpenses/>
  <Transaction/>
  <AddTransaction/>
</template>

<script>
import Header from './components/Header.vue';
import Balance from './components/Balance.vue';
import IncomeExpenses from './components/IncomeExpenses.vue';
import Transaction from './components/Transaction.vue';
import AddTransaction from './components/AddTransaction.vue';

export default {
  components: {
    Header,
    Balance,
    Transaction,
    IncomeExpenses,
    AddTransaction,
  }
}
</script>