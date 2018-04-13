<template>
  <div id="app" class="container">
    <input-field inputname="UserName" placeholder="Enter text here..." position="is-left" icon="fa-user">
    </input-field>


  </div>
</template>

<script>

import InputField from './components/InputField.vue'

export default {
  name: 'app',
  components: {
    InputField,
  }
}
</script>

<style>

</style>
