<template>
  <div>
    <div class="header">
      <b-row>
        <b-col lg="2" col sm="1" class="d-none d-sm-block" ></b-col>
        <b-col lg="2" col sm="3" class="col-4">
          <img id="logo" src="../assets/logo.svg">
        </b-col>
        <b-col lg="2" col sm="2" class="d-none d-sm-block" ></b-col>
        <b-col lg="2" col sm="2" class="display col-4">
          <div class="size">
            <img v-for="n in 4" :key="n" src="../assets/star.svg">
            <img src="../assets/star_half.svg">
            8.4
            <sub>/10</sub>
          </div>
        </b-col>
        <b-col lg="2" col sm="3" class="col-4">
          <div class="imagetext">Lees onze 2083 beoordelingen</div>
          <img src="../assets/feedbackcompany.svg" class="imageposition">
        </b-col>
        <b-col lg="2" col sm="1" class="d-none d-sm-block"></b-col>
      </b-row>
    </div>
    <div class="content">
      <div class="slanted">
        <svg viewBox="0 0 100 100" preserveAspectRatio="none">
          <polygon points="-53,100 100,0 100,100"></polygon>
        </svg>
        <div class="spaces">
          <b-row class="margin">
            <b-col lg="2"></b-col>
            <b-col lg="4">
              <b-container class="box">
                <div class="heading">
                  Bent u onze
                  nieuwe partner?
                </div>
                <div class="brief">
                  Lorem ipsum dolor sit amet, consectetur adipisc-
                  ing elit. Nam consequat arcu sed nulla lacinia, quis
                  blandit eros facilisis. Mauris mattis nec sem nec
                  finibus. Nunc eget leo ut diam imperdiet vehicula
                  ac non elit. Pellentesque nisi neque, sodales nec
                  sem et, condimentum congue ligula. Integer non
                  ullamcorper lacus, sed luctus sapien
                </div>
                <b-button
                  class="buttons btn btn-primary dropdown-toggle"
                  data-toggle="dropdown"
                >De mogelijkheden</b-button>
              </b-container>
            </b-col>
            <b-col lg="4">
              <img src="../assets/timo_partner.svg">
            </b-col>
            <b-col lg="2"></b-col>
          </b-row>
        </div>
      </div>
      <div>
        <b-row class="margin">
          <b-col lg="3"></b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/range.png">
              </div>
              <div class="servicename">Groot bereik</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/freeSignup.png">
              </div>
              <div class="servicename">Gratis aanmelden</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/service.png">
              </div>
              <div class="servicename">Klantenservice</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="3"></b-col>
        </b-row>
        <b-row class="margins">
          <b-col lg="3"></b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/support.png">
              </div>
              <div class="servicename">Support en inzage</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/money.png">
              </div>
              <div class="servicename">Verdien geld</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/quality.png">
              </div>
              <div class="servicename">Kwalitatief aanbod</div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="3"></b-col>
        </b-row>
        <b-row class="margins">
          <b-col lg="4"></b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/wrench.png">
              </div>
              <div class="servicename">
                Maatwerk
                oplossingen
              </div>
              <div class="servicebrief">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="2">
            <b-container class="borders">
              <div class="image">
                <img src="../assets/thumbs.png">
              </div>
              <div class="servicename">Gemak</div>
              <div class="servicebriefs">
                Lorem ipsum dolor sit amet,
                consectetur adipiscing elit. Nam
                consequat arcu sed nulla lacinia,
                quis blandit eros facil.
              </div>
            </b-container>
          </b-col>
          <b-col lg="4"></b-col>
        </b-row>
      </div>
    </div>
    <div class="footer">
      <b-row>
        <b-col lg="2"></b-col>
        <b-col lg="3">© 2013 - 2019 Vliegenenparkeren.nl - Alle rechten voorbehouden</b-col>
        <b-col lg="2"></b-col>
        <b-col lg="3">Bedrijfsgegevens / Privacy policy / Algemene voorwaarden / Sitemap</b-col>
        <b-col lg="2"></b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
export default {
  name: "Vliegen"
};
</script>

<style>
.header {
  background-color: #e6ffff;
  background-image: url("../assets/cloud.svg");
  background-position: center;
  
  background-size: cover;
  position: relative;
  border-bottom: 30px solid #66b3ff !important;
  height: 120px;
}
.imagetext {
  font-size: 8px;
  position: absolute;
  bottom: 50%;
  right: 24%;
}
.imageposition {
  position: absolute;
  width: 70%;
  bottom: 41%;
}
#logo {
  position: absolute;
  top: 7%;
}
img {
  overflow: hidden;
  padding: 0;
  margin: 0;
  padding-top: 2% !important;
  width: 100%;
}
.display {
  display: flex;
}
.spaces {
  padding-bottom: 5%;
}
.size {
  height: 20%;
  display: flex;
  position: relative;
  width: 89%;
  font-size: 15px;
  margin: auto;
}
.margins {
  margin: 0 !important;
  padding-top: 3% !important;
}
.margin {
  margin: 0 !important;
  padding-top: 5% !important;
}
.container {
  border: 1px solid white;
  background-color: white;
  padding: 20px !important;
}
.box {
  box-shadow: 0 0 15px rgb(0, 0, 0, 0.1);
  padding-bottom: 40px !important;
  padding: 25px !important;
}
.buttons {
  background-color: #66b3ff !important;
  color: white !important;
  margin-top: 10%;
  border: none !important;
  font-size: 13px !important;
  font-weight: bold !important;
  margin-bottom: 8%;
}
.dropdown-toggle::after {
  margin-left: 4em !important;
}
.content {
  background-color: whitesmoke;
  padding-bottom: 5%;
}
.heading {
  font-size: 32px;
  font-weight: bold;
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1;
  text-shadow: 2px 0px floralwhite;
  margin-top: 3%;
}
.brief {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 13px;
  margin-top: 10%;
}
.servicename {
  font-weight: bold;
  text-align: center;
  margin-top: 10%;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
}
sub {
  color: skyblue;
  font-size: 20px;
}
.servicebrief {
  margin-top: 6%;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 0.7em;
}
.servicebriefs {
  margin-top: 22.5%;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 0.7em;
}
.borders {
  border-bottom: 7px solid #66b3ff !important;
}
.image {
  margin: auto;
  height: 55px;
  width: 55px;
}
.footer {
  background-color: #264d73;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 9px;
  padding-top: 1%;
  padding-bottom: 1%;
}
.slanted {
  position: relative;
  background-image: linear-gradient(#f5f5f5, #f5f5f5);
}
.row {
  width: 100%;
  height: inherit;
}
.col-lg-2 {
  height: inherit;
}
svg {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 23vw;
  fill: #ffffff;
}
@media only screen and (max-width: 425px) {
  #logo {
    top:15%;
  }
  .imagetext{
    right: 0%;
  }
}
</style>
