<template>
    <nav>
        <v-app-bar color="white" dark app class="line">
    <v-toolbar-title headline>
        <v-app-bar-nav-icon color="black" text class="ml-2 mb-1" @click="drawer = !drawer"></v-app-bar-nav-icon>
     <span class="font-weight-light black--text">Nike</span>
     <span class="red--text">Outlet</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn text class="mr-1" color="black">Unite</v-btn>
    <v-divider
      color="black"
      class="mx-1 "
      vertical
    ></v-divider>
   <v-btn text class="mr-6" color="black" :to="{name:'Login'}">Inicia Sesion</v-btn>
    <v-btn color="red" small absolute bottom right fab>
        <v-icon>mdi-plus</v-icon>
    </v-btn>
        </v-app-bar>
        <v-navigation-drawer v-model="drawer" dark app mini-variant temporary >
            <v-list flat>
                <v-list-item class="mb-12" router to="/Inicio">
                    <v-list-icon-actions>
                        <v-icon>mdi-home</v-icon>
                    </v-list-icon-actions>
                </v-list-item>
                <v-list-item class="mb-6 mr-5">
                    <v-list-icon-actions>
                        
                    </v-list-icon-actions>
                </v-list-item>
                <v-list-item router to="/">
                <v-list-item-actions>
                    <v-icon>mdi-basketball</v-icon>
                </v-list-item-actions>
                </v-list-item>
                <v-list-item router to="/">
                    <v-list-item-actions>
                       <v-badge color="red">
                       <template v-slot:badge>1</template>
                       <v-icon>mdi-shopping</v-icon>
                       </v-badge>
                    </v-list-item-actions>
                </v-list-item>
                <v-list-item router to="/">
                    <v-list-item-actions>
                        <v-icon>mdi-magnify</v-icon>
                    </v-list-item-actions>
                </v-list-item>
                <v-list-item router to="/">
                    <v-list-item-actions>
                        <v-icon>mdi-cog</v-icon>
                    </v-list-item-actions>
                </v-list-item>
            </v-list>
        </v-navigation-drawer>
    </nav>
</template>

<script>
export default {
    data(){
        return{
            drawer: true
        }
    }
}
</script>