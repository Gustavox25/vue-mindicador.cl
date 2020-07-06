<template>
  <v-container>
    <InicioSesion/>
    <indicador propfecha="01-07-2020">Llamar a dolar con la fecha de la propiedad</indicador>
  </v-container>
</template>

<script>
// @ is an alias to /src
import indicador from '../components/Home/indicador'
import InicioSesion from '../components/Home/InicioSesion'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    props:{
    propfecha:String
    },
    indicador,
    InicioSesion
  },
  methods:{
    
  },
  data(){
    return {
      b_fecha:'01-07-2020'
    }
  }
}
</script>
