<template>
  <div>
    <div class="container--fluid web--nav py-3">
      <div class="d-flex align-items-center">
        <div class="w-100">
          <img src="@/assets/img/logo.png" width="40%" alt="" />
        </div>
        <div class="w-100">
          <ul class="m-0 d-flex align-items-center justify-content-end" style="gap: 30px">
            <li>Home</li>
            <li>About/FAQs</li>
            <li><router-link to="/login"> Login</router-link></li>
            <li><button>Get Started</button></li>
          </ul>
        </div>
      </div>
    </div>


    <div class="mobile--nav py-3">
      <div class="container--fluid">
        <div class="d-flex align-items-center justify-content-between">
          <img src="@/assets/img/logo.png" width="40%" alt="" />
          <i class="fa fa-bars fa-2x text-dark" @click="drawer = !drawer" aria-hidden="true"></i>
        </div>
      </div>
      <el-drawer
        :visible.sync="drawer"
        direction="ttb"
        size="70%">
        <div class="container--fluid">
        <div class="w-100">
          <ul class="m-0 d-flex flex-column" style="gap:20px">
            <li>Home</li>
            <li>About/FAQs</li>
            <li><router-link to="/login"> Login</router-link></li>
            <li><button>Get Started</button></li>
          </ul>
        </div>
    </div>
      </el-drawer>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return {
      drawer: false
    }
  }
}
</script>