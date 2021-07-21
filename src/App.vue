<template>
  <div id="app">
    <div id="nav">
      <header>
        <!-- Navbar -->
        <nav class="navbar navbar-expand-lg navbar-light bg-white fixed-top">
          <div class="container-fluid">
            <button
              class="navbar-toggler"
              type="button"
              data-mdb-toggle="collapse"
              data-mdb-target="#navbarExample01"
              aria-controls="navbarExample01"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <i class="fas fa-bars"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarExample01">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item active">
                  <router-link class="nav-link" to="/">Home</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/about">About</router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link" to="/projects">Projects</router-link>
                </li>
              </ul>
            </div>
          </div>
        </nav>
        <!-- Navbar -->

        <!-- Jumbotron -->
        <div class="p-5 text-white text-center bg-intro" style="margin-top: 35px;">
          <h1 class="display-3">Stephen's Designs</h1>
          <h4 class="mb-3">Building Blocks of The Web</h4>
          <a class="btn btn-primary btn-lg text-white" href="mailto:stephenbrooks714@gmail.com" role="button">MESSAGE ME</a>
        </div>
        <!-- Jumbotron -->

      </header>
    </div>
    <router-view/>
  </div>
</template>

<script>
import * as mdb from 'mdb-ui-kit';

export default {
  mdb
}
</script>


<style>
@import '~mdb-ui-kit/css/mdb.min.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-bottom: 40px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.bg-intro {
  background: url(https://images.unsplash.com/photo-1423666639041-f56000c27a9a?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1353&q=80) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  padding-top: 30%;
  padding-bottom: 30%;
}
</style>
