<template>
  <Header></Header>
  <main>
  <Nav></Nav>
  <Hat></Hat>
  </main>
</template>

<script>
import Header from "./components/Header.vue";
import Nav from "./components/Nav.vue";
import Hat from './components/Hat.vue';

export default {
  name: 'Kanban Desk',
  components: {
    Header, Nav, Hat
  }
}
</script>
<style lang="scss" scoped>
  main{
    display: flex;
    gap: 20px;
  }
</style>