<template>
    <div class="mt-2">
        <div class="card-body pl-3 text-center">
            <sapn><font-awesome-icon  class="text-primary mt-5" icon="user"/></sapn>
            <h5 class="card-title mt-4">NSTOOL</h5>
            <h6 class="card-title mb-4">CEO</h6>
            <div class="row"> 
                <div class="col-6 mt-3">1 follows</div>
                <div class="col-6 mt-3">1 following</div>
            </div>
        </div>
        <nav class="pl-3 pt-3">
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/"><sapn><font-awesome-icon icon="home"/></sapn>　Dashbord</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/profiles"><sapn><font-awesome-icon icon="user"/></sapn>　 Profile</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/reviews/"><sapn><font-awesome-icon icon="star"/></sapn>　Reviews</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/messages/"><sapn><font-awesome-icon icon="envelope"/></sapn>　Messages</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/nortifications/"><sapn><font-awesome-icon icon="bell"/></sapn>　 Notifications</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/billing/"><sapn><font-awesome-icon icon="home"/></sapn>　Biliings</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/favorites/"><sapn><font-awesome-icon icon="heart"/></sapn>　Favarites</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/techs/"><sapn><font-awesome-icon icon="list-alt"/></sapn>　Technologies</nuxt-link>                    
            <nuxt-link class="nav-link py-3 nav-color" to="/mypages/1/offerings/"><sapn><font-awesome-icon icon="list-alt"/></sapn>　Public Offerings</nuxt-link>
            <nuxt-link class="nav-link py-3 nav-color" to="/"><sapn><font-awesome-icon icon="sign-out-alt"/></sapn>　Logout</nuxt-link>
        </nav>
    </div>
</template>

<script>
export default {
    
}
</script>