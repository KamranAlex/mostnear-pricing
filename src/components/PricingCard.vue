<template>
  <div class="container mt-2 mb-4">
    <div class="row d-flex justify-content-center align-items-center">
      <div class="col-md-3">
        <div class="card">
          <img src="../assets/bizped.png" class="card-img-top" alt="..." />
          <h4 class="brand-title">Bizped</h4>
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10/<span>year</span></h3>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li><small>Post your Business Profile </small></li>
                <li><small>Your vision.</small></li>
                <li><small>Your mission.</small></li>
                <li><small>Your products.</small></li>
                <li><small>Your expertise.</small></li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-danger">Subscribe Now</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/bestdeals.png" class="card-img-top" alt="..." />
          <h4 class="brand-title">Best Deals</h4>
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10/<span>year</span></h3>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li>
                  <small>
                    Post your promotional items here that are exclusively
                    offered at a bargain
                  </small>
                </li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-warning">Subscribe Now</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/jobs.png" class="card-img-top" alt="..." />
          <h4 class="brand-title">Hiring Now</h4>
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10/<span>year</span></h3>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li>
                  <small
                    >Post your Open Positions here that you are currently trying
                    to fill.</small
                  >
                </li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-primary">Subscribe Now</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/handshake.png" class="card-img-top" alt="..." />
          <h4 class="brand-title">Advertisement</h4>
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10/<span>year</span></h3>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li>
                  <small
                    >Upload your Details including your weblink, Images of your
                    facility,etc.</small
                  >
                </li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-info">Subscribe Now</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  width: 16rem;
  height: auto;
  margin: 5px auto;
  border: 1px solid #a497ee;
  box-shadow: 0 0 10px grey;
}
img {
  height: 128px;
  width: 50%;
  margin: auto;
}
.brand-title {
  font-family: 'Poppins', sans-serif;
  margin: 0 auto;
  color: #086597;
}
hr {
  margin-top: 0.75rem;
  margin-bottom: 0;
  margin-left: auto;
  margin-right: auto;
  width: 90%;
  align-self: center;
  border: 0;
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}
.pricing h3 {
  color: #05b2a2;
}
.pricing span {
  font-size: 14px;
}
.card-text {
  text-transform: capitalize;
  color: #6f5bda;
}
.features {
  height: 180px;
}
ul {
  list-style: none;
}
ul li {
  padding-right: 30px;
}
ul li small {
  color: rgb(4, 161, 4);
}

ul li:before {
  content: '✓';
  font-size: 12px;
  margin: auto 6px auto 0;
  color: rgb(4, 161, 4);
}
.leaf-logo {
  height: 35px;
  width: 35px;
  position: absolute;
  bottom: 5px;
  right: 5px;
}
button {
  padding: 4px 8px;
  border-radius: 5px;
  color: #ffffff;
  transition: transform 0.4s;
}
button:hover {
  transform: scale(1.15);
  color: #ffffff;
}
</style>
