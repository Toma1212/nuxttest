<template>
    <div class="row">
        <div class="col-sm-4">
            <div class="card">
                <div class="card-body">
                    <h6 class="card-title">FREE!</h6>
                    <div class="card-text" v-for="free in freeplan" :key="free">
                        <p v-if="free.check">
                            {{ free.title }}<span><font-awesome-icon icon="check"/></span>
                        </p>
                        <p v-else>
                            {{ free.title }}<span><font-awesome-icon icon="times"/></span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="card">
                <div class="card-body">
                    <h6 class="card-title">PROFESSIONAL</h6>
                    <div class="card-text" v-for="professional in professionalplan" :key="professional">
                        <p v-if="professional.check">
                            {{ professional.title }}<span><font-awesome-icon icon="check"/></span>
                        </p>
                        <p v-else>
                            {{ professional.title }}<span><font-awesome-icon icon="times"/></span>
                        </p>
                    </div>
                </div>
            </div>
        </div> 
        <div class="col-sm-4">
            <div class="card">
                <div class="card-body">
                    <h6 class="card-title">ENTERPRISE</h6>
                    <p class="card-text" v-for="enterprize in enterprizeplan" :key="enterprize">
                            {{ enterprize.title }} <span><font-awesome-icon icon="check"/></span>
                    </p>
                </div>
            </div>
        </div> 
    </div> 
</template>

<script>
export default {
    data: function() {
        return {

            freeplan : [
                {title:'One Listing',check: true},
                {title:'Maximum 4 images Per Gallery',check: true},
                {title:'Upgrade Available',check: false},
                {title:'30 Days Abaibaly',check: false},
                {title:'Sidebar Statistics',check: false},
                {title:'Businness Hours',check: false},
                {title:'Price Range',check: false},
                {title:'Contact Form',check: false},
                {title:'Email Address',check: false},
                {title:'Phone',check: false},
                {title:'Website',check: false},
                {title:'Social Networks',check: false},
                {title:'Listning Tags',check: false},
                {title:'Unlimited Video Gallery',check: false},
                {title:'Trial Period',check: false},
                {title:'Period 30 days',check: false},

            ],
            professionalplan : [

                {title:'3 Listing',check: true},
                {title:'Upgrade Available',check: true},
                {title:'30 Days Abaibaly',check: true},
                {title:'Sidebar Statistics',check: true},
                {title:'Contact Form',check: true},
                {title:'Email Address',check: false},
                {title:'Phone',check: false},
                {title:'Website',check: false},
                {title:'Social Networks',check: false},
                {title:'Listning Tags',check: false},
                {title:'8 Image Gallery',check: true},
                {title:'3 Video Gallery',check: true},
                {title:'Trial Period 14 days',check: true},
                {title:'Period 30 days',check: true},

            ],
                    
            enterprizeplan : [
                
                {title:'10 Events',check: true},
                {title:'Upgrade Available',check: true},
                {title:'30 Days Abaibaly',check: true},
                {title:'Sidebar Statistics',check: true},
                {title:'Bussiness Hours',check: true},
                {title:'Price Range',check: true},
                {title:'Contact Form',check: true},
                {title:'Email Address',check: false},
                {title:'Phone',check: false},
                {title:'Website',check: false},
                {title:'Social Networks',check: false},
                {title:'Listning Tags',check: false},
                {title:'Unlimited Image Gallery',check: true},
                {title:'Unlimited Video Gallery',check: true},
                {title:'Trial Period 2 days',check: true},
                {title:'Period 30 days',check: true},
            ],
        }
    },
}
</script>