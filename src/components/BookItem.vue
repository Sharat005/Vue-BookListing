<template>

  <li> {{book.title}} : {{book.author}} - {{book.price}}/-RS </li>

</template>

<script>

export default {
  name: 'BookItem',
  props: ['book']
};
</script>

<style>

li{
  display: block;
  margin: 0 10px;
}

</style>
