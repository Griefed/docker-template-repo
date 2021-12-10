<template>
  <q-page>

    <!-- CONTENT GOES HERE -->

  </q-page>
</template>

<script>
import { api } from "boot/axios";
import { defineComponent, inject } from 'vue';

export default defineComponent({
  name: 'PageIndex',
  setup() {

    const store = inject('store');

    return {
      store,
    }
  },
  methods: {

  },
  mounted() {

  }
})
</script>
