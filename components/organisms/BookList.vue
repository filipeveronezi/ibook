<template>
  <div class="book-list">
    <h2>Listagem de livros</h2>

    <BookCard v-for="book in $books" :key="book.id" :book="book" />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { books } from '@/store'

export default Vue.extend({
  computed: {
    $books() {
      return books.$all
    }
  }
})
</script>

<style scoped></style>
