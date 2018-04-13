<template>
  <div class="field">
    <label class="label">{{inputname}}</label>
    <div class="control has-icons-left">
      <input class="input is-success" type="text" :placeholder="placeholder" v-model="inputEntered">   
      <span :class="[position,'icon is-small']">
        <i :class="['fas', icon]"></i>
      </span>  
    </div>
  </div>
</template>

<script>
export default {
  name: 'InputField',
  props: ['inputname', 'placeholder', 'position', 'icon'],
  data() {
    return {
      inputEntered: "",
    }
  },
  components: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
