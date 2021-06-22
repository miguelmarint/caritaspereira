<template>
  <div>
    <section id="clients" class="section-bg">
      <div class="container">
        <div class="section-header">
          <h3>Compañías</h3>
          <p>Empresas que apoyan nuestra labor.</p>
        </div>

        <div class="row no-gutters clients-wrap clearfix wow fadeInUp">
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Abaco-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Alkosto-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Exito-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Homecenter-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/La-14-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Super-inter-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Olimpica-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Pepsico-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Alpina-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Alqueria-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Diocesis-de-peeira-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6">
            <div class="client-logo">
              <img
                :src="asset('images/Fundación-nutresa-1.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
#clients {
  padding: 60px 0;
  box-shadow: inset 0px 0px 12px 0px rgb(0 0 0 / 10%);
}
.section-bg {
  background: #025228;
}
.container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
.section-header h3 {
  font-size: 40px;
  color: #ffffff;
  text-align: center;
  font-weight: 500;
  position: relative;
}
.section-header p {
  text-align: center;
  margin: auto;
  font-size: 17px;
  padding-bottom: 60px;
  color: #fff;
  width: 50%;
}
#clients .clients-wrap {
  border-top: 1px solid #d6eaff;
  border-left: 1px solid #d6eaff;
  margin-bottom: 30px;
}
#clients .client-logo  {
  padding: 64px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-right: 1px solid #d6eaff;
  border-bottom: 1px solid #d6eaff;
  overflow: hidden;
  background: #fff;
  height: 160px;
  width: 100%;
}
#clients .client-logo img:hover{
  transform: scale(1.2);
}
</style>