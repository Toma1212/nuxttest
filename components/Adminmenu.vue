<template>
    <div class="mt-2">
        <div class="card-body pl-3 text-center">
            <div class="row"> 
                
            </div>
            <sapn><font-awesome-icon  class="text-primary mt-5" icon="user"/></sapn>
            <h6 class="card-title mt-4">User</h6>
            <h5 class="card-title mb-4">xxxxxxxxxxxxxx</h5>
        </div>
        <nav class="pl-3 pt-3">
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/"><sapn><font-awesome-icon icon="home"/></sapn>　Dashbord</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/admin-user"><sapn><font-awesome-icon icon="user"/></sapn>　 Profile</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/advertise"><sapn><font-awesome-icon icon="star"/></sapn>　advertise</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/reviews"><sapn><font-awesome-icon icon="star"/></sapn>　reviews</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/messages/"><sapn><font-awesome-icon icon="envelope"/></sapn>　Messages</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/nortifications/"><sapn><font-awesome-icon icon="bell"/></sapn>　 Notifications</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/offering"><sapn><font-awesome-icon icon="star"/></sapn>　offering</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/tech/"><sapn><font-awesome-icon icon="list-alt"/></sapn>　Technologies</nuxt-link>                    
            <nuxt-link class="nav-link py-3 nav-color" to="/admin/user"><sapn><font-awesome-icon icon="list-alt"/></sapn>　Public Offerings</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/"><sapn><font-awesome-icon icon="sign-out-alt"/></sapn>　Logout</nuxt-link>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>