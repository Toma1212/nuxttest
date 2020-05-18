<template>
    <nav class="py-4 navbar navbar-expand-lg navbar-light">
        <nuxt-link class="navbar-brand ml-5" to="/">ManuTech</nuxt-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <form class="form-inline my-2 mr-5 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="What are you looking for" aria-label="Search">
            <button class="btn my-2 my-sm-0" type="submit">
                <font-awesome-icon icon="search"/> 
            </button>
        </form>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item">
                <nuxt-link class="nav-link" to="/faq">Request for question</nuxt-link>
            </li>
            <li class="nav-item mx-5">
                <a class="btn btn-primary text-white" href="#">Add Listning</a>
            </li>
            <li class="nav-item mx-3">
                <a class="nav-link" href="#"><font-awesome-icon icon="envelope"/> </a>
            </li>
            <li class="nav-item mx-3">
                <a class="nav-link" href="#"><font-awesome-icon icon="bell"/> </a>
            </li>
            <li class="nav-item dropdown mx-3">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                <font-awesome-icon icon="user-circle" style="font-size: 30px"/> 
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="home"/></sapn>Dashbord</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="user"/></sapn>Profile</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="star"/></sapn>Reviews</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="envelope"/></sapn>Messages</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="bell"/></sapn>Notifications</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="home"/></sapn>Biliings</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="heart"/></sapn>Favarites</nuxt-link>
                    <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="list-alt"/></sapn>Listning</nuxt-link>
                    <div class="dropdown-divider"></div>
                        <nuxt-link class="dropdown-item" to="/"><sapn><font-awesome-icon icon="sign-out-alt"/></sapn>Logout</nuxt-link>
                </div>
            </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>