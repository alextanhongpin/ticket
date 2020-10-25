<template>
  <h1>Update Domain</h1>

  <p>
    <label>Name</label>
    <br />
    <input type="text" value="jobs" />
  </p>

  <p>
    <label>Description</label>
    <br />
    <textarea
      placeholder="Enter domain description"
      value="Jobs are services that user are looking to do"
    />
  </p>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({})
</script>
