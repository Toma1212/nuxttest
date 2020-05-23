<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-12 col-xl-2 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="col-12 col-xl-10 py-md-4 bd-content mypage">
                <div class="mypage-content p-4 mx-3 ">
                    <a class="btn btn-primary text-white" href="#"><sapn><font-awesome-icon icon="user"/></sapn>　View Profile</a>
                </div>

                <form>   
                    <div class="mypage-content mx-3 mt-4 p-3">
                        <header class="content-header">
                            <h6>BASIC INFO</h6>
                        </header>

                                <div class="mt-3">
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>First Name<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" value="">
                                        <label>Last Name<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>Display Name<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="mb-2">  
                                    <div class="content-input-body">
                                        <label for="content-input-file">
                                                <p class="float-left mr-100">Avatar</p>
                                                <span class="btn btn-primary text-white float-left ml-100">Upload Image</span>
                                            <input type="file" class="content-input-file" id="content-input-file" style="display:none;">
                                        </label>
                                    </div>
                                </div>

                                <div class="mb-2">  
                                    <div class="content-input-body">
                                        <label for="content-input-file">
                                                <p class="float-left mr-100">Cover Image</p>
                                                <span class="btn btn-primary text-white float-left ml-100">Upload Image</span>
                                            <input type="file" class="content-input-file" id="content-input-file" style="display:none;">
                                        </label>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>Email<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>Position</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>Introduce</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="content-input-body">
                                    <div class="input-group-text mb-20">
                                        <input type="checkbox" aria-label="Checkbox for following text input">
                                    </div>
                                </div>
                        </div>


                    <div class="mypage-content mx-3 mt-4 p-3">
                        <header class="content-header">
                            <h6>FOLOOW&CONTACT</h6>
                        </header>

                                <div class="mt-3">
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>Address<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" value="">
                                        <label>Phone<span style="color:red">*</span></label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="text" placeholder="">
                                        <label>website</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                        </div>
                
                    <div class="mypage-content mx-3 mt-4 p-3">
                        <header class="content-header">
                            <h6>CHANGE PASSWORD</h6>
                        </header>

                                <div class="mt-3">
                                    <div class="content-input-body">
                                        <input class="content-input" type="password" placeholder="">
                                        <label>Current Password</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="password" value="">
                                        <label>New Password</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                                <div class="">  
                                    <div class="content-input-body">
                                        <input class="content-input" type="password" placeholder="">
                                        <label>Confirm Password</label>
                                        <span class="focus_line"></span>
                                    </div>
                                </div>

                        </div>               

                <button class="p-4 mx-3 my-3 btn btn-primary text-white submit-btn" href="#" style="width:98%">Save Changes</button>
                
                </form>

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