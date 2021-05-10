<template>
  <div>
    <section id="services" class="section-bg">
      <div class="container">
        <header class="section-header">
          <h3>Programas</h3>
          <p>
            Laudem latine persequeris id sed, ex fabulas delectus quo. No vel
            partiendo abhorreant vituperatoribus.
          </p>
        </header>

        <div data-aos="fade-up">
          <div class="row">
            <div class="col-md-6 col-lg-5 offset-lg-1 wow bounceInUp">
              <div class="box">
                <div class="icon">
                  <i class="ion-ios-analytics-outline"></i>
                </div>
                <h4 class="title">
                  <a href="">PASTORAL RURAL Y DE LA TIERRA</a>
                </h4>
                <p class="description">
                  La Pastoral Rural y de la tierra es un servicio de Iglesia,
                  que busca acompañar y caminar al lado de los hombres y las
                  mujeres del campo, asumiendo los ritmos y ciclos propios de su
                  entorno, compartiendo el amor por la tierra, sembrando la
                  semilla, nutriéndola y regándola en solidaridad con sus
                  dificultades y esperanzas.
                </p>
                <br />
                <h4 class="criterios">Criterios de Acción</h4>
                <p class="description">
                  <ul class="circle">
                    <li>
                      Se enmarca en el ámbito de la Pastoral Social: Su misión es
                      llevar la Buena Nueva de Jesús resucitado a los hombres y
                      mujeres del campo
                    </li>
                    <li>
                      Tiene una profunda inspiración bíblica: La tierra es don de 
                      Dios y lugar del encuentro con “los otros” y con “el Otro”.
                    </li>
                    <li>
                      Está orientada por la Doctrina Social de la Iglesia: El 
                      trabajo, la propiedad y, la justa distribución de los 
                      bienes y la riqueza son temas centrales.
                    </li>
                  </ul>
                </p>
              </div>
            </div>
            <div class="col-md-6 col-lg-5 wow bounceInUp">
              <div class="box">
                <div class="icon">
                  <i class="ion-ios-bookmarks-outline"></i>
                </div>
                <h4 class="title">
                  <a href="">FORMACIÓN AGENTES DE PASTORAL SOCIAL</a>
                </h4>
                <p class="description">
                  Minim veniam, quis nostrud exercitation ullamco laboris nisi
                  ut aliquip ex ea commodo consequat tarad limino ata
                </p>
              </div>
            </div>
          </div>
        </div>

        <div data-aos="fade-up">
          <div class="row">
            <div class="col-md-6 col-lg-5 offset-lg-1 wow bounceInUp">
              <div class="box">
                <div class="icon">
                  <i class="ion-ios-paper-outline"></i>
                </div>
                <h4 class="title">
                  <a href="">RESPONSABILIDAD SOCIAL EMPRESARIAL</a>
                </h4>
                <p class="description">
                  Duis aute irure dolor in reprehenderit in voluptate velit esse
                  cillum dolore eu fugiat nulla pariatur
                </p>
              </div>
            </div>
            <div class="col-md-6 col-lg-5 wow bounceInUp">
              <div class="box">
                <div class="icon">
                  <i class="ion-ios-speedometer-outline"></i>
                </div>
                <h4 class="title"><a href="">ACCIÓN VOLUNTARIA</a></h4>
                <p class="description">
                  Excepteur sint occaecat cupidatat non proident, sunt in culpa
                  qui officia deserunt mollit anim id est laborum
                </p>
              </div>
            </div>
          </div>
        </div>

        <div data-aos="fade-up">
          <div class="row">
            <div class="col-md-6 col-lg-5 offset-lg-1 wow bounceInUp">
              <div class="box">
                <div class="icon">
                  <i class="ion-ios-world-outline"></i>
                </div>
                <h4 class="title"><a href="">BANCO DE ALIMENTOS</a></h4>
                <p class="description">
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui
                  blanditiis praesentium voluptatum deleniti atque
                </p>
              </div>
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
#services {
  padding: 60px 0 40px 0;
  box-shadow: inset 0px 0px 12px 0px rgb(0 0 0 / 10%);
}

#services .section-header h3 {
  font-size: 36px;
  color: #0c0c0c;
  text-align: center;
  font-weight: 500;
  position: relative;
}
#services .section-header p {
  text-align: center;
  margin: auto;
  font-size: 15px;
  padding-bottom: 60px;
  color: #556877;
  width: 50%;
}

#services .row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
#services .box {
  padding: 30px;
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  margin: 0 10px 40px 10px;
  background: #fff;
  box-shadow: 0 10px 29px 0 rgb(68 88 144 / 10%);
  transition: all 0.3s ease-in-out;
}
#services .icon {
  position: absolute;
  left: -10px;
  top: calc(50% - 32px);
}
#services .icon i {
  font-size: 64px;
  line-height: 1;
  transition: 0.5s;
}
#services .title {
  margin-left: 40px;
  font-weight: 700;
  margin-bottom: 15px;
  font-size: 19px;
}
#services .title a {
  color: #111;
}
#services .description {
  font-size: 16px;
  margin-left: 40px;
  line-height: 24px;
  margin-bottom: 0;
  text-align: justify;
}
#services .criterios {
  margin-left: 40px;
  font-weight: 700;
  margin-bottom: 15px;
  font-size: 19px;
  color: #111;
}

#services ul{
  list-style: none;
  font-size: 16px;
  text-align: justify;
}

.section-bg {
  background: #ecf5ff;
}
</style>