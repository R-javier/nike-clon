<template>
    <v-container>
    <v-footer height="300%" width="100%" class="mt-0 pt-0">
     <v-row md3 class="mb-15">
        
        <v-flex >
                
          <v-card-text class="px-0 font-weight-bold">LOCALES MÁS CERCANOS</v-card-text>
          <v-card-text class="px-0 font-weight-bold">REGISTRATE PARA RECIBIR NOVEDADES</v-card-text>
        
      

      </v-flex>

</v-row>


<v-row md2 class="mt-12 ">       
    <v-flex class=" mr-15">
        
         
         <v-card-text class="px-0 font-weight-bold">ACERCA DE NIKE</v-card-text>
        
              
                <v-list-item class="px-0" router to="/">
              
                    <p class="text-caption " >Noticias</p>
                
                </v-list-item>
                <v-list-item class="px-0" router to="/">
                 <p class="text-caption">Empleo</p>
                </v-list-item>
                <v-list-item class="px-0" router to="/">
                   <p class="text-caption">Inversores</p>
                </v-list-item>
                <v-list-item class="px-0" router to="/">
                   <p class="text-caption">Sustentabilidad</p>
                </v-list-item>
          
      </v-flex>
    </v-row>


    <v-spacer></v-spacer>

<v-row md6 class="mb-5">
    <v-flex>
        <v-btn text fab><v-icon>mdi-twitter</v-icon></v-btn>
        <v-btn text fab><v-icon>mdi-facebook</v-icon></v-btn>
        <v-btn text fab><v-icon>mdi-youtube</v-icon></v-btn>
        <v-btn text fab><v-icon>mdi-instagram</v-icon></v-btn>
    </v-flex>
    
    </v-row>
    
 
 
    
    </v-footer>
    <v-divider class="mt-5 pt-4"></v-divider>
<v-footer>
    <v-row>
        
        <v-icon>mdi-map-marker</v-icon>
        <p class="mt-5 font-weight-bolder">Argentina</p>
        <p class="mt-5 ml-5 font-weight-bolder">© 2021 Nike, Inc. Todos los derechos reservados.</p>
        <v-spacer ></v-spacer>
        <v-card-actions>
            <v-btn text class="text-caption">Términos de uso</v-btn>
            <v-btn text class="text-caption">Política de privacidad</v-btn>
        </v-card-actions>
     </v-row>
</v-footer>
    
</v-container>
</template>


<script>
export default {
    name:'Footer'
}
</script>