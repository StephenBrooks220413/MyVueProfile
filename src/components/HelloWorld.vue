<template>
  <div class="hello">
    <div class="container">
      <div class="row">
        <div class="col-md mt-5">
          <img 
            src="https://images.unsplash.com/photo-1581291518857-4e27b48ff24e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" 
            alt="pattern"
            class="img-fluid"
          />
        </div>
        <div class="col-md mt-5">
          <h3>Laying It Out</h3>
          First I get the big picture, consisting
          of business needs, your type of business, 
          and hte consumer market you are focused on.
          <br><br>
          <a href="mailto:stephenbrooks714@gmail.com" class="btn btn-dark">LEARN MORE</a>
        </div>
        
      </div>
      <!-- <br><br><br> -->
      <div class="row">
        <div class="col-md mt-5">
          <h3>All Devices</h3>
          I understand that your website must look 
          good on all devices. The style I use is built 
          mobile first and expands to desktops.
          <br><br>
          <a href="mailto:stephenbrooks714@gmail.com" class="btn btn-dark">LEARN MORE</a>
        </div>
        <div class="col-md mt-5">
          <img 
            src="https://images.unsplash.com/photo-1496171367470-9ed9a91ea931?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" 
            alt="pattern"
            class="img-fluid"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello {
  margin-bottom: 20px;
}
</style>
