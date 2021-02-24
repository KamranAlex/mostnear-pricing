<template>
  <div class="container mt-2 mb-4">
    <div class="row d-flex justify-content-center align-items-center">
      <div class="col-md-3">
        <div class="card">
          <img src="../assets/bizped.png" class="card-img-top" alt="..." />
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10 / <span>month</span></h3>
              <hr />
            </div>

            <div class="description mt-2">
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-danger">Subscribe</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/bestdeals.png" class="card-img-top" alt="..." />
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10 / <span>month</span></h3>
              <hr />
            </div>

            <div class="description mt-2">
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-warning">Subscribe</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/jobs.png" class="card-img-top" alt="..." />
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10 / <span>month</span></h3>
              <hr />
            </div>

            <div class="description mt-2">
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-primary">Subscribe</button>
            </div>
          </div>

          <img src="../assets/leaflogo.jpg" alt="" class="leaf-logo" />
        </div>
      </div>

      <div class="col-md-3">
        <div class="card">
          <img src="../assets/handshake.png" class="card-img-top" alt="..." />
          <hr />
          <div class="card-body">
            <div class="pricing">
              <h3>$10 / <span>month</span></h3>
              <hr />
            </div>

            <div class="description mt-2">
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
              <hr />
            </div>

            <div class="features mt-2">
              <h5 class="text-center">Features:</h5>

              <ul>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
                <li><small>Lorem ipsum dolor.</small></li>
              </ul>
            </div>
            <div class="subscribe-btn mt-4">
              <button class="btn-info">Subscribe</button>
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
  height: 170px;
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
/* .features h5 {
  color: #ca048f;
} */
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
  color: #000000;
}
</style>
