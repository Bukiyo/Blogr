<template>
  <nav class="navbar navbar-expand-lg navbar-dark mt-5">
    <div class="container">
    <a class="navbar-brand mr-5" href="#">
      <img src="@/assets/logo.svg" class="img-fluid" width="30" height="30" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        
        <li class="nav-item dropdown dropdown-hover">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Product
          </a>
          <div class="dropdown-menu dropdown-hover-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>

        <li class="nav-item dropdown dropdown-hover">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Company
          </a>
          <div class="dropdown-menu dropdown-hover-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>

        <li class="nav-item dropdown dropdown-hover">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Connect
          </a>
          <div class="dropdown-menu dropdown-hover-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Contact</a>
            <a class="dropdown-item" href="#">Newsletter</a>
            <a class="dropdown-item" href="#">Linkedin</a>
          </div>
        </li>

      </ul>
      <form class="form-inline my-2 my-lg-0">
        <button class="btn my-2 my-sm-0 btnLogin" type="submit">Login</button>
        <button class="btn ml-2 my-sm-0 btnSign" type="submit">Sign Up</button>
      </form>
    </div>
  </div>
</nav>

<button type="button" class="btn btn-dark displayBtn" @click="changeBtnIcon" data-toggle="modal" data-target="#exampleModal">
  <svg v-if="btnStatus" xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16">
    <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"/>
  </svg>
  <svg v-else xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x-lg" viewBox="0 0 16 16">
  <path d="M1.293 1.293a1 1 0 0 1 1.414 0L8 6.586l5.293-5.293a1 1 0 1 1 1.414 1.414L9.414 8l5.293 5.293a1 1 0 0 1-1.414 1.414L8 9.414l-5.293 5.293a1 1 0 0 1-1.414-1.414L6.586 8 1.293 2.707a1 1 0 0 1 0-1.414z"/>
  </svg>
</button>

<!-- Modal -->
<div @click="reverseIcon"  class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button  type="button" class="close closeMdl" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button  type="button" class="btn btn-secondary closeMdl" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>

</template>


<script>
import $ from 'jquery';
export default {
  data() {
    return {
      btnStatus: true
    };
  },
  methods: {
    changeBtnIcon () {
      this.btnStatus = !this.btnStatus;
      $('#exampleModal').modal('show');
    },
    reverseIcon () {
      this.btnStatus = !this.btnStatus;
    }
 
  }
};
</script>

<style scoped>
  form button {
    border-radius: 25px;
    width: 7rem;
  }

  form button:hover {
    background-color: hsl(355, 100%, 74%);
    color: white;
  }

  .btnLogin {
    color: white;
  }

  .btnSign {
    background-color: white;
    color: hsl(356, 100%, 66%);
    font-weight: bold;
  }

  .dropdown a:hover {
    text-decoration: underline;
  }

  .nav-link {
    color: white !important;
  }

  @media only screen and (min-width: 960px) {
    .dropdown-hover:hover .dropdown-hover-menu {
      display: block;
      margin-top: 0;
    }

    .dropdown-hover:hover .dropdown-toggle::after {
      border-bottom: 0.3em solid;
      border-top: 0;
    }
  }

  .dropdown-menu a:hover {
    text-decoration: none;
    font-weight: bold;
  }

  .dropdown-item:focus, .dropdown-item:hover {
    color: #16181b;
    background-color: transparent;
  }

  .img-fluid {
    width: 6rem;
  }

  .displayBtn {
    display: none;
  }

</style>