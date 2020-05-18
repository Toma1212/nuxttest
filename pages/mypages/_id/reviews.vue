<template>
    <div class="container-fluid">
        <div class="row flex-xl-nowrap">
            <div class="col-12 col-md-3 col-xl-2 bd-sidebar">
                <mypageMenu />
            </div>
            <main class="col-12 col-md-9 col-xl-10 py-md-5 bd-content mypage">
                <div class="dashboard">

                    <div class="row"> 
                        <div class="col-11 col-lg-11 mypage-content p-4 mx-5 ">
                            <div class="input-group">
                                <input type="text" placeholder="Newest Rating" class="form-control" aria-label="Text input with segmented dropdown button">
                                <div class="input-group-append">
                                    <button type="button" class="btn"><font-awesome-icon icon="times"/></button>
                                    <button type="button" class="btn dropdown-toggle dropdown-toggle-split" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    <span class="sr-only">Toggle Dropdown</span>
                                    </button>
                                        <div class="dropdown-menu">
                                        <a class="dropdown-item" href="#">Action</a>
                                        <a class="dropdown-item" href="#">Another action</a>
                                        <a class="dropdown-item" href="#">Something else here</a>
                                        <div role="separator" class="dropdown-divider"></div>
                                        <a class="dropdown-item" href="#">Separated link</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="row"> 
                        <div class="col-11 col-lg-11 mypage-content p-5 mx-5 mt-4">
                            <table class="table">
                                <thead >
                                    <tr>
                                        <th>
                                            <span><font-awesome-icon icon="share-alt-square"/></span>TITLE
                                        </th>
                                        <th>DETAILS</th>
                                        <th>CONTENT</th>
                                        <th>LISTING TITLE</th>
                                        <th>MORE</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>a</td>
                                        <td>a</td>
                                        <td>a</td>
                                        <td>a</td>
                                        <td><button class="btn btn-primary text-white">hide</button></td>
                                    </tr>
                                        <tr>
                                        <td>a</td>
                                        <td>a</td>
                                        <td>a</td>
                                        <td>a</td>
                                        <td><button class="btn btn-primary text-white">hide</button></td>
                                    </tr>
                                </tbody>
                                <tfoot>
                                    <tr>
                                        <td colspan="4">
                                        </td>
                                        <a class="mt-2">back</a>
                                    </tr>
                                </tfoot>
                            </table>
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