<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-3 col-xl-2 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="col-12 col-md-9 col-xl-10 py-md-5 bd-content" style="background-color:green;">
            
            </main>
        </div>
    </div>
</template>

<script>
import mypageMenu from '~/components/mypageMenu.vue'
import planupgrade from '~/components/planupgrade.vue'

export default {
    components: {
        mypageMenu,
    },
}
</script>