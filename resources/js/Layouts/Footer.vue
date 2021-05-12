<template>
  <div>
    <footer id="footer">
      <div class="footer-top">
        <div class="container">
          <div class="row">
            <div class="col-sm footer-info">
              <img :src="asset('images/imagotipo-fundacion-caritas-1.png')" alt="">
              <p><strong>
                Somos la labor social de la Iglesia Católica. En todo el mundo
                tiene una palabra que la identifica, CÁRITAS, que significa
                CARIDAD.</strong>
              </p>
            </div>

            <div class="col-sm footer-links">
              <h4>Useful Links</h4>
              <ul>
                <li><a href="">Home</a></li>
                <li><a href="">About us</a></li>
                <li><a href="">Services</a></li>
                <li><a href="">Terms of service</a></li>
                <li><a href="">Privacy policy</a></li>
              </ul>
            </div>

            <div class="col-sm footer-contact">
              <h4>Contáctanos</h4>
              <p>
                Cra 20 # 4-47 <br />
                Pereira y Sede Banco de Alimentos :<br />
                Transversal 5 # 6-30 Calle de las Aromas la Badea Dosquebradas
                <br />
                <strong>Teléfono:</strong> (+57)321 6467811 – (+57)3148962397 -
                Fijo 3154138<br />
                <strong>Correo electrónico:</strong>
                comunicaciones@caritaspereira.org<br />
              </p>

              <div class="social-links">
                <a href="" class="twitter"><i class="fab fa-twitter"></i></a>
                <a href="" class="facebook"
                  ><i class="fab fa-facebook-f"></i
                ></a>
                <a href="" class="instagram"
                  ><i class="fab fa-instagram"></i
                ></a>
                <a href="" class="google-plus"
                  ><i class="fab fa-google-plus-g"></i
                ></a>
                <a href="" class="linkedin"
                  ><i class="fab fa-linkedin-in"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {};
</script>
<style  scoped>
#footer {
  background: #ffffff;
  padding: 0 0 30px 0;
  color: #eee;
  font-size: 14px;
}
#footer .footer-top {
  background: #025228;
  padding: 60px 0 30px 0;
}
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
#footer .footer-top .footer-info {
  margin-bottom: 30px;
}
#footer .footer-top .footer-links {
  margin-bottom: 30px;
}
#footer .footer-top .footer-contact {
  margin-bottom: 30px;
}
#footer .footer-top .footer-info h3 {
  font-size: 34px;
  margin: 0 0 20px 0;
  padding: 2px 0 2px 0;
  line-height: 1;
  font-family: "Arial Narrow";
  color: #fff;
  font-weight: 400;
  letter-spacing: 3px;
  text-transform: uppercase;
}
#footer .footer-top .footer-info p {
  font-size: 20px;
  line-height: 24px;
  margin-bottom: 0;
  font-family: "Arial Narrow";
  color: #ecf5ff;
  text-align: justify;
}
#footer .footer-top h4 {
  font-size: 14px;
  font-weight: bold;
  color: #fff;
  text-transform: uppercase;
  position: relative;
  padding-bottom: 10px;
}

#footer .footer-top .footer-links ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
#footer .footer-top .footer-links ul li:first-child {
  padding-top: 0;
}
#footer .footer-top .footer-links ul li {
  padding: 8px 0;
}
#footer .footer-top .footer-links ul a {
  color: #ecf5ff;
}
#footer .footer-top .footer-contact p {
  line-height: 26px;
}
#footer .footer-top .social-links a {
  font-size: 18px;
  display: inline-block;
  background: #ffffff;
  color: #028341;
  line-height: 1;
  padding: 8px 0;
  margin-right: 4px;
  border-radius: 50%;
  text-align: center;
  width: 36px;
  height: 36px;
  transition: 0.3s;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
}
b,
strong {
  font-weight: bolder;
}
</style>

