<template>
  <fragment>
      <Title />
      <Search />
      <Body v-bind:query="query"/>
      <Footer />
 </fragment>
</template>

<script>
import Title from './Title'
import Search from './Search'
import Body from "./Body"
import Footer from './Footer'

export default {
  name: "Home",
  components: {
      Title,
      Search,
      Body,
      Footer
  },
  props: [
      "query"
  ]
}
</script>

<style>

</style>