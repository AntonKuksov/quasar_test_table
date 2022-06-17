<template>
  <q-layout view="lHh Lpr lFf">

    <q-page-container>
      <Table/>
    </q-page-container>
  </q-layout>
</template>

<script>
import { ref } from 'vue'
import Table from './components/Table.vue'

export default {
  name: 'LayoutDefault',

  components: {
    Table
  },

  setup () {
    return {
      leftDrawerOpen: ref(false)
    }
  }
}
</script>
