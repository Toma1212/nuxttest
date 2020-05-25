<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-2 col-xl-2 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="col-12 col-md-10 col-xl-10 py-md-4 bd-content mypage">
                <userprofile />
            </main>
        </div>
    </div>
</template>

<script>
import mypageMenu from '~/components/mypageMenu.vue'
import userprofile from '~/components/profile/userprofile.vue'

export default {
    components: {
        mypageMenu,
        userprofile
    },
}
</script>