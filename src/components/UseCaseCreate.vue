<template>
  <h1>Create UseCase</h1>

  <p>
    <label>Name</label>
    <br />
    <input type="text" value="create user" />
  </p>

  <p>
    <label>
      <input type="radio" name="read-write" value="read" checked />
      Read
    </label>
    <label>
      <input type="radio" name="read-write" value="write" />
      Write
    </label>
  </p>

  <p>
    <label>Importance</label>
    <br />
    <input type="number" placeholder="Enter 1-5" />
  </p>
  <p>
    <label>User Story</label>
    <br />
    <textarea
      placeholder="Enter user story"
      value="As a user\nI want to add jobs\nIn order to populate the entry"
    />
  </p>

  <p>
    <label>Description</label>
    <br />
    <textarea
      placeholder="Enter domain description"
      value="Jobs are services that user are looking to do"
    />
  </p>

  <p>
    <label>User Story</label>
    <br />
    <textarea
      placeholder="Enter user story"
      value="As a user\nI want to add jobs\nIn order to populate the entry"
    />
  </p>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({})
</script>
