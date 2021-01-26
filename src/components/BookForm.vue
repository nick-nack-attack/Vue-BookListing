<template>
  <form class="" action="#" method="post" onsubmit="e => bookSubmit(bookTitle, bookAuthor)">
    <input type="text" name="title" value="" placeholder="Book Title">
    <input type="text" name="author" value="" placeholder="Book Author">
    <button type="submit" name="button">Add Book</button>
  </form>
</template>

<script>
export default {
  name: "BookForm",
  props: ['books'],
  date() {
    return {
      bookTitle: '',
      bookAuthor: ''
    }
  }
}
</script>

<style scoped>

</style>
