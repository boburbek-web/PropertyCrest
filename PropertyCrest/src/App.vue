<template>
  <main class="text-white">
    <div class="container">
      <div class="navbar p-3 align-items-center">
        <div class="col-6">
          <h5>PropertyCrest</h5>
        </div>
        <div class="col-6">
          <ul
            class="navbar__ul d-flex w-100 justify-content-between list-unstyled align-items-center"
          >
            <li><a class="nav-link" href="#">Home</a></li>
            <li><a class="nav-link" href="#">About</a></li>
            <li><a class="nav-link" href="#">Real Estate</a></li>
            <li><a class="nav-link" href="#">Construction</a></li>
            <li><a class="nav-link" href="#">Consultancy</a></li>
            <li><a class="nav-link" href="#">Contact Us</a></li>
            <li class="navbar__ul__li_btn text-center">
              <a class="nav-link" href="#">Get Started</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="col-4">
        <div class="mainContentBox pt-5">
          <h1 class="mainContentheader1 fw-bold">Find your place of dream</h1>
          <p class="h5">
            We are glad to have you around. Feel free to browse our website.
          </p>

          <div class="input-box">
            <input
              type="text"
              class="form-control"
              placeholder="Find a location"
            />
            <i class="fa fa-search search"></i>
          </div>
        </div>
      </div>
    </div>
  </main>

  <div class="container">
      <div class="wrapper d-flex">
        <div class="wrapper__left  d-flex">
          <div class="wrapper__left__circle">
            <img src="./assets/video.png" alt="">
          </div>
          <p class="wrapper__left__p m-2">Watch how <span style="color:#3F51F4">Property</span> <span style="color:#0193FD">Crest</span> works <br>Presented by PropertyCrest CEO</p>
        </div>


        <div class="wrapper__right  d-flex flex-column align-items-end text-end">
          <h1 style="color: #0193FD;" class="text">
            Be a co-Landlord <br />
            <span style="color:#3F51F4;">Brick by Brick</span>
          </h1>
          <p>
            Through the power of the group, you no longer have to wait to gather
            a small fortune in order to invest in real estate. Our fractional
            ownership platform allows you to pool with others in order to buy a
            small bit of a big property.
          </p>

          <div class="more text-center">Learn More</div>
        </div>
      </div>
  </div>
</template>

<script></script>

<style>
main {
  height: 768px;
  background-image: url(./assets/main.png);
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  font-family: "Montserrat";
}

.navbar__ul__li_btn {
  width: 142px;
  height: 40px;
  border: 1px solid white;
  padding: 6px;
  border-radius: 20px;
}
.mainContentBox {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 341px;
}
.mainContentheader1 {
  font-size: 50px;
}

.input-box {
  position: relative;
}

.input-box i {
  position: absolute;
  right: 20px;
  top: 15px;
  color: #ced4da;
}
.input-box .search {
  color: #0193fd;
}
.form-control {
  border-radius: 30px;
  height: 50px;
 
  color: #eeeeee69;
}
.wrapper{
  position: relative;

}

.wrapper .wrapper__left{
  width: 66.66666667%;
  height: 80px;
}
.wrapper .wrapper__left .wrapper__left__circle img{
  width: 62px;

}
.wrapper .wrapper__left .wrapper__left__p{
  font-style: italic;
}

.wrapper .wrapper__right{
  width: 33.33333333%;
    position: absolute;
    top: -13rem;
    right: 0%;
}
.wrapper .more {
  width: 142px;
  height: 40px;
  padding: 6px;
  border: 1px solid #3f51f4;
  border-radius: 43px;
}
</style>
