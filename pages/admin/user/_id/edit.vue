<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-2 col-xl-2 bd-sidebar">
                <Adminmenu />
            </div>
            <main class="col-12 col-md-10 col-xl-10 py-md-5 bd-content mypage">
                <userprfile />
            </main>
        </div>
    </div>
</template>

<script>
import Adminmenu from '~/components/Adminmenu.vue'
import userprfile from '~/components/profile/userprofile.vue'

export default {
    components: {
        Adminmenu,
        userprfile,
    },
}
</script>