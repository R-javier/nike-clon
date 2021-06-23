<template>
  <v-parallax
  class="mt-1"
   height="450"
  
    src="portadita.jpg"
  >
   <v-container>
        
        <v-row class="justify-center align-content-center">
       <v-card class="pa-5 mt-2" height="350">
        <v-form>
            <v-text-field label="Ingrese usuario o mail" color="error">
            </v-text-field>
            <v-text-field label="Ingrese Contraseña" color="error">
            </v-text-field>
            <v-card-actions>
                <v-btn color="error" block class="mb-2">Sign up</v-btn>
                </v-card-actions>
                <v-row>
                <p class="mt-5 ml-5">Already have an account?</p><v-btn class="ma-3 ml-1 pl-2" color="error" text>Log in</v-btn>
                </v-row>
                <v-row>
                <p class="mt-4 ml-4">Did you forget your password?</p><v-btn class="ma-2 ml-1 pl-2" color="error" text>Log in</v-btn>
                </v-row>
            
        </v-form>
        </v-card>
        </v-row>
    </v-container>
  
  
  
  
  
  </v-parallax>
</template>