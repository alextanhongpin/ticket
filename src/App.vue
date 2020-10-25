<template>
  <domain-list />
  <domain-edit />
  <use-case-create />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import DomainList from './components/DomainList.vue'
import DomainEdit from './components/DomainEdit.vue'
import UseCaseCreate from './components/UseCaseCreate.vue'

export default defineComponent({
  name: 'App',
  components: {
    DomainList,
    DomainEdit,
    UseCaseCreate
  }
})
</script>
