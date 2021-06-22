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
                  <input type="radio" id="credito" value="targeta-credito" />
                  <label for="credito"> Tarjeta de Crédito</label>
                  <br />
                  <input type="radio" id="paypal" value="pago-paypal" />
                  <label for="paypal"> PayPal</label>
                </div>
                <br />
                <div class="donate">
                  <p>Tipo de donación</p>
                  <input type="radio" id="anon" value="don-anonima" />
                  <label for="anon"> Deseo que mi donación sea anónima</label>
                  <br />
                  <input type="radio" id="data" value="fac-datos" />
                  <label for="data">
                    No tengo problema en facilitar mis datos</label
                  >
                </div>
              </div>
            </div>

            <div class="col-md-6 col-lg-6">
              <div class="container-pay">
                <div class="method">
                  <div class="reference">
                    <q style="text-align: justify">
                    LA POBREZA NO LA HIZO DIOS, LA HACEMOS TÚ Y YO CUANDO NO
                    COMPARTIMOS LO QUE TENEMOS.
                  </q>
                  </div>
                  <br>
                  <i style="font-size:20px">Madre Teresa</i>
                  <br><br>
                  <div class="info">
                    <i class="fas fa-map-marker-alt"></i>
                    <p>
                      Calle 20 Nro 4-47 Pereira y Sede Banco de Alimentos : Transversal 5
                      # 6-30 Calle de las Aromas la Badea Dosquebradas
                    </p>
                  </div>
                </div>
                <br />
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
          </div>
        </div>
        <button type="button" class=" btn btn btn-outline-dark mr-4">Siguiente</button>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
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
#donation .radio{
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
  background-color: #025228;
  color: #fff;
  font-size: 17px;
  font-family: "Arial Narrow";
  border-radius: 10px;
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
  border:1px dashed;
}
#donation .btn {
  font-size: 25px;
  color: rgb(224, 209, 209);
  border-width: 1.5px;
}
</style>