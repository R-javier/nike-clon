<template>
<v-container>
  <v-app>
    <v-toolbar app max-height="60" white flat fluid class="mt-5">
      <v-app-bar-nav-icon>
        
         <img  src="nike.svg" width="80px">
      </v-app-bar-nav-icon>
      <v-spacer></v-spacer>
      <v-list class="mr-5">
        
        <v-list-items  class="ma-2">
          <v-list-actions>
            <v-btn  text>Colecciones</v-btn>
          </v-list-actions>
        </v-list-items>
        <v-list-items class="ma-2">
          <v-list-actions>
            <v-btn text>Unite a Nosotros</v-btn>
          </v-list-actions>
        </v-list-items>
        <v-list-items class="ma-2">
          <v-list-actions>
            <v-btn text>Nike Journal</v-btn>
          </v-list-actions>
        </v-list-items>
        <v-list-items class="ma-2">
          <v-list-actions>
            <v-btn text>Tiendas</v-btn>
          </v-list-actions>
        </v-list-items>
        <v-list-items  class="ma-2">
          <v-list-actions>
            <v-btn text>SNKRS</v-btn>
          </v-list-actions>
        </v-list-items>
       
      </v-list>
       <v-spacer></v-spacer>
      
    </v-toolbar>

   <v-img
      src="portada.jpg" class="mt-12" size="100px" alt="">
   </v-img>
    

    <v-row class="pt-6">
        <v-col class="d-flex justify-center mt-12" > 
          
            <v-btn rounded color="black" class="white--text text-lowercase pa-5">Conocé más</v-btn>
     
        </v-col>
    </v-row>

    <v-row wrap height="100vh pt-5 mt-5">
      <v-flex md6 class="mt-8 pr-5" >
          <v-img
          src="imgizq.jpg" class="white--text align-end">
          
          <v-card-text class="black--text pb-0 font-weight-medium ml-3 " >Celebrá el Día del Padre</v-card-text>
          <v-card-title class="black--text display-2 font-weight-bold ml-3 ">TU PRIMER <br> ENTRENADOR</v-card-title>
          <v-card-actions class="ml-3 pa-5">
          <v-btn color="black" rounded class="white--text pa-5 font-weight-light">Comprar</v-btn>
          </v-card-actions>
         
          </v-img>
      </v-flex>

      <v-flex md6 class="mt-8 pr-5">
          <v-img
          src="imgdere.jpg" class="white--text align-end">

           <v-card-text class="white--text pb-0 font-weight-medium ml-3 " >Nike Yoga Collection</v-card-text>
          <v-card-title class="white--text display-2 font-weight-bold ml-3 ">RESPIRÁ. ESTIRATE.<br> MOVETE.</v-card-title>
          <v-card-actions class="ml-3 pa-5">
          <v-btn color="white" rounded class="black--text pa-5">Ver mas </v-btn>
          <v-btn color="white" rounded class="black--text pa-5">Comprar</v-btn>
          </v-card-actions>
          </v-img>
      </v-flex>
      
    </v-row>

    <v-row wrap height="100vh" class="mt-6 pt-5">
      <v-flex md6 class="mt-12 pr-5" >
          <v-img
          src="imgizq2.jpg" class="white--text align-end">
          
          <v-card-text class="white--text pb-0 font-weight-medium ml-3 " >Wmns Air Force 1 Crater</v-card-text>
          <v-card-title class="white--text display-2 font-weight-bold ml-3 ">MOVE TO ZERO</v-card-title>
          <v-card-actions class="ml-3 pa-5">
          <v-btn color="white" rounded class="black--text pa-5">Ver mas </v-btn>
          <v-btn color="white" rounded class="black--text pa-5">Comprar</v-btn>
          </v-card-actions>
         
          </v-img>
      </v-flex>

      <v-flex md6 class="mt-12 pr-5">
          <v-img
          src="img-dere2.jpg" class="white--text align-end">

          <v-card-title class="white--text display-2 font-weight-bold ml-3 ">NIKE BLAZER</v-card-title>
          <v-card-actions class="ml-3 pa-5">
          <v-btn color="white" rounded class="black--text pa-5">Ver mas </v-btn>
          <v-btn color="white" rounded class="black--text pa-5">Comprar</v-btn>
          </v-card-actions>
          </v-img>
      </v-flex>
      
    </v-row>

    <v-row class="mt-5 pt-5">

        <v-img src="portada 2.jpg" class="mt-12 white--text align-end "> 
          <v-card-title class="display-2 font-weight-bold ml-5">NIKE ACG</v-card-title>
          <v-card-actions>
            <v-btn rounded class="pa-5 ml-6">Ver Mas</v-btn>
            <v-btn rounded class="pa-5 ml-6">Comprar</v-btn>
          </v-card-actions>

        </v-img>
      
    </v-row>

    <v-row class="mt-5 pt-5">
      <v-img src="portada 3.jpg" class="mt-12 white--text align-end">
         <v-card-title class="display-2 font-weight-bold ml-5">LA NUEVA <br> GENERACIÓN DE <br> VELOCIDAD</v-card-title>
          <v-card-actions class="pa-6">
            <v-btn rounded class="pa-5 ml-6">Ver Mas</v-btn>
            <v-btn rounded class="pa-5 ml-6">Comprar</v-btn>
          </v-card-actions>

      </v-img>
    </v-row>

   <v-row wrap height="100vh" class="mt-6 pt-5">
      <v-flex md6 class="mt-12 pr-5" >
          <v-img
          src="portada4.jpg" class="white--text text-center align-center">
          
          <v-card-text class="white--text pb-0 font-weight-medium ml-3 mt-15 pt-5">
            <p class="text-md-center">Live Expert Sessions</p>
           <p class="text-md-center display-1" >NIKE STORE <br>ALTO PALERMO </p>
            <p >Comprá online y <br> recibilo en tu casa.</p>
            </v-card-text>
          <v-card-title></v-card-title>
          <v-card-actions class="ml-5 justify-center">
          <v-btn color="white" rounded class="black--text pa-5 ">Comprar</v-btn>
          </v-card-actions>
         
          </v-img>
      </v-flex>

      <v-flex md6 class="mt-12 pr-5">
          <v-img
          src="portada5.jpg" class="white--text align-center">

           <v-card-text class="white--text pb-0 font-weight-medium ml-3 mt-15 pt-5">
            <p class="text-md-center display-2">NUESTRAS<br>TIENDAS</p>
            <p class="text-md-center">Conocé el estado de<br>todas nuestras tiendas.</p>
            </v-card-text>
          <v-card-title></v-card-title>
          <v-card-actions class="ml-5 justify-center">
          <v-btn color="white" rounded class="black--text pa-5 ">NIKE STORES</v-btn>
           <v-btn color="white" rounded class="black--text pa-5 ">FACTORY STORES</v-btn>
          </v-card-actions>
          </v-img>
      </v-flex>
      
    </v-row>

    <v-row >
      <v-flex md6 class="mt-12 pr-5">
        <v-img
        src="portada6.jpg"
        >
        </v-img>
        <v-card-actions class="justify-center">
          <v-btn rounded color="black" class="white--text pa-5 ma-6 font-weight-light" >Comprar</v-btn>
        </v-card-actions>
      </v-flex>


      <v-flex md6 class="mt-12 pr-5">
        <v-img
          src="portada7.jpg">
        </v-img>
        <v-card-actions class="justify-center">
          <v-btn rounded color="black" class="white--text pa-5 ma-6 font-weight-light" >Ver más</v-btn>
        </v-card-actions>
      </v-flex>
    </v-row>

    <v-row class="font-weight-medium mt-6 mb-6 ">
      <h2>Últimos Lanzamientos</h2>
    </v-row>

    <v-row>
      <v-img src="portada 6.jpg"></v-img>
      <v-card-text >
        <p class="d-flex justify-center mt-5 mb-0 font-weight-bold">El lugar para tus Sneakers.</p>
        <h2 class="d-flex justify-center display-1 font-weight-bold black--text mb-3">SNKRS</h2>
        <v-card-actions class="justify-center">
          <v-btn rounded class="white--text pa-5 font-weight-light" color="black">Ver más</v-btn>
        </v-card-actions>
      </v-card-text>
    </v-row>

    <v-row class="font-weight-medium mt-6 mb-6 ">
      <h2>Seguí entrenando y corriendo</h2>
    </v-row>

    <v-row wrap height="100vh pt-5 mt-5">
      <v-flex md6 class="mt-8 pr-5" >
          <v-img
          src="portada8.jpg" class="white--text align-end mb-5">
          
          </v-img>
          <v-card-title >
            <h3 >Nike Training Club App</h3>
          </v-card-title>
          <v-card-text class="pb-2">
            <p class="font-weight-bold">Tu mejor entrenador personal.</p>
          </v-card-text>
          <v-card-actions class="pt-0">
            <v-btn class="white--text pa-5 ml-2 font-weight-light" rounded color="black">Descargar</v-btn>
          </v-card-actions>
      </v-flex>

      <v-flex md6 class="mt-8 pr-5">
          <v-img
          src="portada9.jpg" class="white--text align-end">

          </v-img>
          <v-card-title class="mt-5">
            <h3> Nike Run Club App</h3>
          </v-card-title>
          <v-card-text class="pb-2">
            <p class="font-weight-bold">La motivación que necesitás para correr más y mejor.</p>
          </v-card-text>
          <v-card-actions class="pt-0 mb-5">
            <v-btn class="white--text pa-5 ml-2 font-weight-light" rounded color="black">Descargar</v-btn>
          </v-card-actions>
      </v-flex>
      
    </v-row>

  
    
  </v-app>
  </v-container>

 
  </template>

