<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-4 col-xl-3 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="col-12 col-md-8 col-xl-6 py-md-5 bd-content">
            
            </main>
            <div class="d-none d-xl-block col-md-3 col-lx-3 bd-toc p-5" style="background-color:blue;">
                axa
            </div>
        </div>
    </div>
</template>

<script>
import mypageMenu from '~/components/mypageMenu.vue'

export default {
    components: {
        mypageMenu
    },
}
</script>