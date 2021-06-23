<template>
  <v-app>
    <v-container>
    <v-row cols="12" md="4">
      <v-col >
        <v-text-field label="Buscar" prepend-icon="mdi-magnify" color="dark" white></v-text-field>
      </v-col>
      <v-spacer></v-spacer>
      <span class="black--text mt-9 mr-5" >50 items</span>
      <v-btn text class="mt-7">
        <v-icon color="red" class="mr-n0">mdi-menu</v-icon>
      </v-btn>
        <v-btn text class="mt-7">
        <v-icon color="red" class="mr-n0">mdi-view-dashboard</v-icon>
      </v-btn>
    </v-row>
    <v-row>
      <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa9.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
              NIKE DUNK HI RETRO
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa2.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
             WMNS JORDAN 11 RETRO
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>

       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa3.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
              JORDAN 1 LOW
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa4.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
              JORDAN 1 MID
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa7.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
             NIKE AIR RUBBER DUNK 
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa8.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
              NIKE DUNK HI SP
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa10.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
             NIKE FLYLEATHER AF1 QS
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>


       <v-col cols="12" md="3" class="mb-4">
        <v-hover v-slot:default="{ hover } ">
          <v-card max-width="250" max-height="250" align="center">
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn icon><v-icon>mdi-pencil</v-icon></v-btn>
            </v-card-actions>
            <v-img src="zapa11.jpg" width="240" height="150"> </v-img>
            <v-card-text class="red--text">
              NIKE FLYLEATHER BLAZER '77 QS
              </v-card-text>
            <v-expand-transition>
              <div 
                  v-if="hover"
            class="d-flex transition-fast-in-fast-out red v-card--reveal display-3 white--text"
            style="height: 100%;">
                <v-btn outlined color="white">Detail</v-btn>
               </div>
               
            </v-expand-transition>
            <v-btn
          absolute
          color="red"
          class="white--text"
          fab
          small
          left
          top
        >
          <h1>1</h1>
        </v-btn>
          </v-card>
        </v-hover>
      </v-col>
    </v-row>
    </v-container>
  </v-app>
</template>

<script>
  

  export default {
    name: 'Home',

    components: {
     
    },
    computed:{
      theme() {
        return (this.$vuetify.theme.dark) ? 'dark' : 'light'
      }
    }
  }
</script>


<style>
.v-card--reveal{
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%

}
</style>