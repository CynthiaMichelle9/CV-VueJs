<template>

  <Cv Run="22.222.222-2" Apellidos="MUSK" Nombres="ELON REEVE" Nacionalidad="SUDAFRICANO" Sexo="M" FechaNacimiento="28 JUN 1971" NumeroDocumento="222.222.222" FechaEmision="01 ENE 2025" FechaVencimiento="01 ENE 2030"/>

</template>

<script>

import CurriculumVitae from './components/cv.vue';

export default {
  name: 'App',
  components: {
    Cv: CurriculumVitae
  }
}
</script>

<style>

</style>
