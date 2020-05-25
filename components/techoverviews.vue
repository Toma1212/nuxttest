<template>
    <div class="row"> 
        <div class="col-lg-3 col-md-6 col-sm-12" v-for="n of 8" :key="n">
            <v-card
                max-width="344"
                class="mx-auto"
            >

                <v-img
                src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg"
                height="194"
                ></v-img>

                <v-list-item>
                <v-list-item-avatar color="grey">
                    <v-img
                    class="elevation-6"
                    src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg"
                    ></v-img>
                </v-list-item-avatar>
                <v-list-item-content class="px-2">
                    <v-list-item-title class="headline">Title</v-list-item-title>
                    <v-list-item-subtitle>name</v-list-item-subtitle>
                </v-list-item-content>
                </v-list-item>

                <v-card-text>
                テキストテキストテキストテキストテキストテキストテキストテキスト
                </v-card-text>

                <v-card-actions>
                    <v-list-item-avatar color="grey">
                        <v-img
                        class="elevation-6"
                        src="https://cdn.vuetifyjs.com/images/cards/mountain.jpg"
                        ></v-img>
                    </v-list-item-avatar>
                    <v-list-item-content　class="mx-2" >
                        <v-list-item-title>Manufacture</v-list-item-title>
                    </v-list-item-content>
                    <v-spacer></v-spacer>
                    <v-btn icon>
                        <font-awesome-icon icon="search"/>
                    </v-btn>
                    <v-btn icon>
                        <v-icon>mdi-heart</v-icon>
                    </v-btn>
                </v-card-actions>
            </v-card>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>