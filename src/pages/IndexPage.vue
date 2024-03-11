<template>
  <h1 class="center">Quasar Form</h1>
  <q-page class="flex flex-center alineTop">
    <!-- <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    > -->
    <From />
  </q-page>

</template>

<script>
import { defineComponent } from 'vue'
import From from '../components/Form.vue'

export default defineComponent({
  name: 'IndexPage',
  components: {
    From
  }

})
</script>

<style scoped>
.center {
  text-align: center;
}

</style>
