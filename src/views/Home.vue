<template>
  <div class="container text-center mt-5 mb-5">
    <h1>My Design Pattern</h1>
    <br>
    <div class="row">
      <div class="col-md m-3">
        <i class="fab icon-m fa-mdb"></i>
        <br>
        Styling with Material Design with Bootstrap5
      </div>
      <div class="col-md m-3">
        <i class="fab icon-f fa-vuejs"></i>
        <br>
        Using the lightweight JavaScript framework Vue.js
      </div>
      <div class="col-md m-3">
        <i class="fab icon-n fa-node"></i>
        <br>
        Communicating with API to deliver dynamic content
      </div>
    </div>
    <br><br>
    <HelloWorld />
    <br><br>
    <h1 class="display-4">Recent Projects</h1>
    <br>
    <div class="row">
      <div class="col-md m-3">
        <label for="">Barber Shop</label> <br>
        <a href="https://barber-cuts.netlify.app/" target="_blank">
          <img
            src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="img-thumbnail hover-shadow"
            alt="..."
          />
        </a>
      </div>
      <div class="col-md m-3">
        <label for="">Hair Innovation</label> <br>
        <a href="https://www.innovationhairclinic.net/" target="_blank">
          <img
            src="https://images.unsplash.com/photo-1562322140-8baeececf3df?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
            class="img-thumbnail hover shadow"
            alt="..."
          />
        </a>
      </div>
      <div class="col-md m-3">
        <label for="">Candle Shop</label> <br>
        <a href="https://candle-shop.netlify.app/" target="_blank">
          <img
            src="https://images.unsplash.com/photo-1570823635306-250abb06d4b3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1350&q=80"
            class="img-thumbnail hover-shadow"
            alt="..."
          />
        </a>
      </div>
      <div class="col-md m-3">
        <label for="">Mobile Nails</label> <br>
        <a href="https://mobile-nail-care.netlify.app/" target="_blank">
          <img
            src="https://images.unsplash.com/photo-1464917423479-6bd9527d469f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1353&q=80"
            class="img-thumbnail hover-shadow"
            alt="..."
          />
        </a>
      </div>
    </div>
    <br>
    <div class="container mt-5 mb-5 fluid text-center">
      <h1 class="display-3">Schedule A Consultation</h1>
      <!-- Start Square Appointments Embed code --><a style=" background-color: #006aff; color: white; height: 40px; text-transform: uppercase; font-family: 'Square Market', 'helvetica neue', helvetica, arial, sans-serif; letter-spacing: 1px; line-height: 38px; padding: 0 28px; border-radius: 3px; font-weight: 500; font-size: 14px; cursor: pointer; display: inline-block; " href="https://calendly.com/stephenbrooks/15min" target="_blank">Book an Appointment</a><!-- End Square Appointments Embed code -->
      <br>
      <img 
        src="https://stephencook.files.wordpress.com/2020/11/wateryearcalendar.jpg" 
        alt=""
        style="width:370px; height: 300px;"
      />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style>
.icon-m {
  font-size: 3.3em;
  color: blue;
}
.icon-f {
  font-size: 3.3em;
  color: green;
}
.icon-n {
  font-size: 3.3em;
  color: rgb(152, 204, 109);
}
</style>