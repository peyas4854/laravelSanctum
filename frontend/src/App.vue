<template>

  <div id="nav">

      <navbar></navbar>
  </div>

  <router-view />

</template>
<script>
import navbar from "@/components/Navbar";


export default {
    components:{
        navbar
    }
}

</script>

