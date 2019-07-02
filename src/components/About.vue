<template>
  <div class="about">
    <h1>This is {{ their_name }}'s To Do list developed in Vue.Js.</h1>
    
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>