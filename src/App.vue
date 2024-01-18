<template>
  <Header />
  <div class="container">
    <Balance />
    <IncomeExpenses />
    <TransactionList />
    <AddTransaction />
  </div>
</template>
<script setup>
import AddTransaction from '@/components/AddTransaction.vue'
import Balance from '@/components/Balance.vue'
import Header from '@/components/Header.vue'
import IncomeExpenses from '@/components/IncomeExpenses.vue'
import TransactionList from '@/components/TransactionList.vue'
</script>