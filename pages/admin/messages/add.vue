<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-3 col-xl-2 bd-sidebar">
                <Adminmenu />
            </div>
            <main class="col-12 col-md-9 col-xl-10 py-md-5 bd-content" style="background-color:green;">
            
            </main>
        </div>
    </div>
</template>

<script>
import Adminmenu from '~/components/Adminmenu.vue'

export default {
    components: {
        Adminmenu,
    },
}
</script>