<template>
<div>
    <section id="donation" class="clearfix">
      <div class="container">
        <header class="section-header">
          <h3 class="section-title">!Haz aquí tu donación¡</h3>
          <li style="list-style: number">
            Elige la cantidad con la que quieres colaborar
          </li>
        </header>
        <div class="container-form">
          <div class="row">
            <div class="col-md-6 col-lg-6">
              <div class="container-pay">
                <div class="method">
                  <p>Método de pago</p>
                  <div class="form-check">
                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
                    <label class="form-check-label" for="flexRadioDefault1">
                      Default radio
                    </label>
                  </div>
                  <div class="form-check">
                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
                    <label class="form-check-label" for="flexRadioDefault2">
                      Default checked radio
                    </label>
                  </div>
                </div>
                <br />
                <div class="donate">
                  <p>Tipo de donación</p>
                  <div class="form-check">
                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
                      <label class="form-check-label" for="flexRadioDefault1">
                      Default radio
                    </label>
                  </div>
                  <div class="form-check">
                    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
                    <label class="form-check-label" for="flexRadioDefault2">
                      Default checked radio
                    </label>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-md-6 col-lg-6">
              <div class="container-pay">
                <div class="method">
                  <div class="reference">
                    <q>
                      LA POBREZA NO LA HIZO <br />
                      DIOS, LA HACEMOS TÚ Y YO CUANDO NO COMPARTIMOS LO QUE
                      TENEMOS.
                    </q>
                  </div>
                  <br />
                  <i style="font-size: 20px">Madre Teresa</i>
                  <br /><br />
                  <div class="info">
                    <i class="fas fa-map-marker-alt"></i>
                    <p>
                      Calle 20 Nro 4-47 Pereira y Sede Banco de Alimentos :
                      Transversal 5 # 6-30 Calle de las Aromas la Badea
                      Dosquebradas
                    </p>
                  </div>
                </div>
                <div class="donate">
                  <p>Importe</p>
                  <div class="input">
                    <select class="form" id="importe">
                      <option selected>10.000</option>
                      <option value="1">20.000</option>
                      <option value="2">30.000</option>
                      <option value="3">40.000</option>
                      <option value="3">50.000</option>
                      <option value="3">Más de 50.000</option>
                    </select>
                  </div>
                </div>
              </div>
            </div>
            <button type="button" v-bind:href="formdonations" class="btn btn-outline-dark mr-4">
            <strong>Siguiente</strong>
            <VoluntaryForm />
            </button>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import DonationsForm from "./DonationsForm";
export default {
  components: {DonationsForm},
};
</script>
<style scoped>
#donation {
  padding: 60px 0;
  box-shadow: 0px 0px 12px 0px rgb(0 0 0 / 10%);
  background-color: #025228;
}

.section-header h3 {
  font-size: 40px;
  color: #fff;
  text-align: center;
  font-weight: 500;
  position: relative;
}
.section-header li {
  text-align: left;
  font-size: 17px;
  padding-bottom: 30px;
  color: #fff;
  width: 50%;
  font-family: "Arial Narrow";
}

#donation .row {
  width: 100%;
  height: 100vh;
  position: relative;
  overflow: hidden;

}

#donation .container-pay {
  padding: 30px;
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  margin: 0 10px 40px 10px;
  background-color: #ffff;
}

#donation input {
  font-size: 32px;
}
#donation .radio {
  background-color: #025228;
}

#donation p {
  font-size: 19px;
  color: #000;
  font-weight: normal;
  font-family: "Arial Narrow";
}

#donation label {
  padding-left: 10px;
  padding-bottom: 20px;
  font-size: 17px;
  font-family: "Arial Narrow";
}

#donation .reference {
  width: 500px;
  height: 80px;
  -moz-border-radius: 50%;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  background-color: #025228;
  color: #fff;
  font-size: 17px;
  font-family: "Arial Narrow";
  text-align: center;
}

#donation .info i {
  font-size: 32px;
  color: #025228;
  float: left;
  line-height: 1;
}

#donation .info p {
  padding: 0 0 10px 36px;
  line-height: 28px;
  font-size: 17px;
  font-family: "Arial Narrow";
}

#donation .form {
  background-color: #025228;
  color: #fff;
  font-size: 25px;
  width: 200px;
  border: 1px dashed;
}
#donation .btn {
  font-size: 18px;
  color: rgb(224, 209, 209);
  border-width: 1.5px;
}

#donation .button  {
  display: flex;
  justify-content: center;
}

#donation .btn-outline-dark:hover {
  background: #799b9173;
}

</style>