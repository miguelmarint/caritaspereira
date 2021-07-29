<template>
  <div>
    <app-layout>
      <template #titleSection
        ><h3 class="d-inline align-middle"></h3></template
      >
      <h1 class="mt-4">Fundación Cáritas Admin</h1>
      <p>
        Panel de administración.
      </p>
    </app-layout>
  </div>
</template>

<script>
import AppLayout from "@/Layouts/AppLayout";

export default {
  components: {
    AppLayout,
  },
  methods: {},
};
</script>