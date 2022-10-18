<template>
    <div>
      <div>
        <footer class="footer mt-4">
          <div class="container--fluid py-3">
            <div class="footer--top">
              <div class="row">
                <div class="col-md-4 mb-3">
                  <img src="@/assets/img/logo.png" width="300" alt="">
                  <div class="mt-2">
                    <h4 class="text-white footer--header">Visit our office </h4>
                    <p>3 Idowu Taylor St, Victoria Island, Lagos, Nigeria.</p>
                  </div>
                </div>
                <div class="col-md-2">
                  <h4 class="footer--header">Quicklinks</h4>
                  <ul class="list-unstlyed">
                    <li><router-link to="/">Get Started</router-link></li>
                    <li><router-link to="/">About Us</router-link></li>
                    <li><router-link to="/">Privacy Policy</router-link></li>
                    <li><router-link to="/">News & Update</router-link></li>
                  </ul>
                </div>

                <div class="col-md-3 mb-3">
                  <div class="mb-3">
                    <h4 class="footer--header">Call Us on</h4>
                    <div class="d-flex" style="gap:10px">
                        <a href="tel:+234 01-2703010">+234 01-2703010</a>
                        <a href="tel:+234 01-2802623">+234 01-2802623</a>
                    </div>
                  </div>
                  <div class="">
                    <h4 class="footer--header">Write Us at</h4>
                    <a href="mailto:payarenavs@up-ng.com">payarenavs@up-ng.com</a>
                  </div>
                </div>
                
                <div class="col-md-3">
                  <h4>Products of Unified Payments</h4>
                  <!-- <h6 class="text-white">Follow Us</h6> -->
                  <ul class="list-unstlyed">
                    <li>
                      <a target="_blank" href="#">
                        PayAttitude
                      </a>
                    </li>
                    <li>
                      <a target="_blank" href="#">
                        PayArena
                      </a>
                    </li>
                    <li>
                      <a target="_blank" href="#">
                        Up Agency Netwrok
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
  
            <div class="footer--copyright">
              <hr class="w-50 mx-auto bg-secondary" />
              <div class="d-lg-flex align-items-center justify-content-around">
                <div>
                <p class="text-center small">
                    2022 © Payarena Verification Service. Copyright All Rights Reserved.
                </p>
              </div>
              <div >
                <ul class="m-0 d-flex align-items-center justify-content-center" style="gap:30px">
                    <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                    <li> <a href="#"> <i class="fa fa-twitter" aria-hidden="true"></i> </a> </li>
                    <li> <a href="#"> <i class="fa fa-linkedin" aria-hidden="true"></i> </a> </li>
                    <li> <a href="#"> <i class="fa fa-instagram" aria-hidden="true"></i> </a> </li>
                </ul>
              </div>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </div>
  </template>