<template>
<p>Welcome to Vue {{name}} loves {{wife}} A/F!</p>
<p v-text="question"></p>  <!-- note v-directive is within selector like p -->
<p v-html="htmlData" v-bind:id="id" v-bind:class="id" v-bind:style="style"></p>
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      name: 'Robert M Hendricks',
      wife: 'Jacqueline T Hendricks',
      question: 'How are you',
      htmlData: '<b>I am html</b>',
      id: 'new',
      style: {
        color: 'purple',
        backgroundColor: 'violet'
      }
    }
  },
  components: {

  }
}
</script>

<style> 
</style>
