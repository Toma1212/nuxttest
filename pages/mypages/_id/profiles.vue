<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-3 col-xl-2 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="ccol-12 col-md-9 col-xl-10 py-md-5 bd-content mypage">
                    <div class="row"> 
                        <div class="col-11 col-lg-11 mypage-content p-4 mx-5 ">
                            <a class="btn btn-primary text-white" href="#"><sapn><font-awesome-icon icon="user"/></sapn>　View Profile</a>
                        </div>
                    </div>

                    <div class="row"> 
                        <div class="col-11 col-lg-11 mypage-content p-4 mx-5 mt-4">
                            <h5>Featured</h5>
                                <div class="">
                                    <h5 class="">Special title treatment</h5>
                                    <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
                                    <a href="#" class="btn btn-primary">Go somewhere</a>
                                </div>
                            </div>
                        </div>
            </main>
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