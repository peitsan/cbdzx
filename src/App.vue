<script>
  import Moderlizer from './components/Moderlizer';
  import Thesiser from "./components/Thesiser";
  import pm from "./components/PM"

  import formore from "./components/formore";
  import Coder from "./components/Coder";
  import Aboutus from "./components/aboutus";
  import contactus from "./components/contactus";
  import dhl from "./components/dhl";
  import transition from "./components/transition";

  "use strict";

  export default {
    name: 'first',
    components: {
      "v-moderlizer":Moderlizer,
      "v-transition":transition,
      "v-code":Coder,
      "v-thesiser":Thesiser,
      "v-pm":pm,
      "v-foremore":formore,
      "v-Aboutus":Aboutus,
      "v-contactus":contactus,
      "v-danghang":dhl,
    }
}
</script>
<template >
  <div id="first" class="bw" >
    <v-danghang></v-danghang>
    <!-- <v-transition></v-transition> -->=
    <v-moderlizer></v-moderlizer>
    <v-code></v-code>
    <v-thesiser></v-thesiser>
    <div id="second" >
  
    <v-Aboutus></v-Aboutus>
    <v-contactus></v-contactus>
    <v-foremore></v-foremore>
    <router-view/>
  </div>
  </div>
</template>
<style scoped>
   
</style>
