<template>
  <Header></Header>
  <Nav></Nav>
</template>

<script>
import Header from "./components/Header.vue";
import Nav from "./components/Nav.vue";
export default {
  name: 'Kanban Desk',
  components: {
    Header, Nav
  }
}
</script>
<style lang="scss" scoped>

</style>