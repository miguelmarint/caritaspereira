<template>
  <div>
    <section id="about">
      <div class="container">
        <header class="section-header">
          <h3>Sobre nosotros</h3>
          <p>
            En la diócesis de Pereira la labor de pastoral social se inició a
            partir de su creación. Ante la necesidad de atender a las víctimas
            del terremoto ocurrido en el eje cafetero en 1999. Pero desde el 31
            de mayo de 2000 Monseñor Fabio Suescún Mutis creo la fundación
            Caritas Diocesanas para brindar una plataforma legal y jurídica que
            permitiera canalizar recursos provenientes del estado de entidades
            de cooperación internacional, empresas privadas y personas en
            general que se solidarizaron con la tragedia. Inicialmente los
            programas y acciones se centraron en la atención a la población
            desplazada y víctimas de la violencia, mediante convenios realizados
            con la Presidencia de la Republica, ONGS internacionales, algunas
            alcaldías y la gobernación de Risaralda. De igual manera se
            acompañaron programas de diferentes entes gubernamentales dirigidos
            al desarrollo social y económico de población situación de
            vulnerabilidad.
          </p>
        </header>
        <div data-aos="fade-up">
          <div class="row about-container">
            <div class="col-lg-6 content order-lg-1 order-2">
              <div class="icon-box wow">
                <div class="icon"><i class="fas fa-hand-holding-heart"></i></div>
                <h4 class="title"><a href="">Misión:</a></h4>
                <p class="description">
                  Trabajamos por la cultura de la solidaridad, la justicia, la
                  dignidad humana, la transformación social y la inclusión con
                  equidad, favoreciendo preferencialmente a los más pobres,
                  fundamentados en la Caridad de CRISTO.
                </p>
              </div>

              <div class="icon-box wow">
                <div class="icon"><i class="fas fa-bible"></i></div>
                <h4 class="title"><a href="">Visión:</a></h4>
                <p class="description">
                  Ser la Pastoral Social de la región, con mayor incidencia en
                  la construcción de una sociedad más justa, que apoya la
                  defensa de la vida, la dignidad humana y la construcción de
                  paz, por medio de la evangelización de las realidades
                  sociales.
                </p>
              </div>

              <div class="icon-box wow">
                <div class="icon"><i class="fas fa-people-carry"></i></div>
                <h4 class="title"><a href="">Objetivo</a></h4>
                <p class="description">
                  Ser instrumento del Área de Promoción Humana para ayudar y
                  servir a los más desprotegidos de la Diócesis sin distinción
                  de raza, religión o política.
                </p>
              </div>
            </div>

            <div class="col-lg-6 background order-lg-2 order-1 wow">
              <img
                :src="asset('images/inicio.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
          </div>
        </div>

        <div data-aos="fade-up">
          <div class="row about-extra">
            <div class="col-lg-6 wow">
              <img
                :src="asset('images/tenequipo.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>
            <div class="col-lg-6 wow pt-5 pt-lg-0">
              <h4>Valores Corporativos</h4>  
                <div class="ready">
                  <div><i class="fas fa-praying-hands"></i>
                  Fe.
                </div>
                <div><i class="fas fa-cross"></i> 
                  Esperanza.
                </div> 
                <div><i class="fas fa-heart"></i> Caridad</div> 
                <div><i class="fas fa-balance-scale"></i> Justicia.</div> 
                <div><i class="far fa-hand-paper"></i> Dignidad humana.</div> 
                <div><i class="fas fa-recycle"></i> Compromiso ambiental.</div> 
                <div><i class="far fa-handshake"></i> Compromiso ético.</div>
                <div><i class="fas fa-hand-holding-medical"></i> Bien común.</div>
                <div><i class="far fa-building"></i> Responsabilidad</div>
                <div><i class="fas fa-hand-holding-medical"></i> La verdad.</div> 
              </div>
            </div>
          </div>
        </div>
        <div data-aos="fade-up">
          <div class="row about-extra">
            <div class="col-lg-6 wow order-1 order-lg-2">
              <img
                :src="asset('images/nosotros-caritas.jpg')"
                class="img-fluid"
                alt=""
              />
            </div>

            <div class="col-lg-6 wow pt-4 pt-lg-0 order-2 order-lg-1">
              <h4>Nuestros Objetivos</h4>
              <ul>
                <br>
                <li>
                  Ser instrumento del Área de Promoción Humana para ayudar y
                  servir a los más desprotegidos de la Diócesis sin distinción
                  de raza, religión o política.
                </li>
                <li>
                  Presentar, promover, apoyar y/o ejecutar proyectos generadores
                  de empleo, vivienda, educación, salud, recreación y protección
                  del medio ambiente, teniendo en cuenta la realidad
                  socio-cultural de las comunidades.
                </li>
                <li>
                  Promover, apoyar y ejecutar programas y proyectos de
                  capacitación que brinden la posibilidad de mejorar la calidad
                  de vida de las comunidades.
                </li>
                <li>
                  Gestionar, apoyar y ejecutar programas y proyectos encaminados
                  a promover la seguridad alimentaria y nutricional a través de
                  la recolección de alimentos con destino al cubrimiento de
                  necesidades de la población en general así como también
                  procurar a través de campañas el desperdicio cero de
                  alimentos.
                </li>
                <li>
                  Gestionar, promover, apoyar y ejecutar programas y proyectos
                  encaminados a la defensa, protección y promoción de los
                  derechos humanos y el acceso a la justicia.
                </li>
              </ul>
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
#about {
  background: #fff;
  padding: 60px 0;
}
#about .section-header h3 {
  font-size: 38px;
  color: #0c0c0c;
  text-align: center;
  font-weight: 500;
  position: relative;
}
#about .section-header p {
  text-align: center;
  margin: auto;
  font-size: 16px;
  padding-bottom: 60px;
  color: #0c0c0c;
  width: 50%;
  text-align: justify;
}
#about .row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
#about .about-container .content {
  background: #fff;
}
#about .about-container p {
  line-height: 26px;
}
#about .about-container .icon-box {
  background: #fff;
  background-size: cover;
  padding: 0 0 30px 0;
}
#about .about-container .icon-box .icon {
  float: left;
  background: #fff;
  width: 64px;
  height: 64px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  border-radius: 50%;
  border: 2px solid #028341;
  transition: all 0.3s ease-in-out;
}
#about .about-container .icon-box .icon i {
  color: #028341;
  font-size: 24px;
}
#about .fa-shopping-bag:before {
  content: "\f290";
}
#about .about-container .icon-box .title {
  margin-left: 80px;
  font-weight: 600;
  margin-bottom: 5px;
  font-size: 19px;
}
#about .about-container .icon-box .title a {
  color: #0c0c0c;
}
#about .about-container .icon-box .description {
  margin-left: 80px;
  line-height: 24px;
  font-size: 16px;
  text-align: justify;
}
#about .about-container .background {
  margin: 20px 0;
}
#about .img-fluid {
  max-width: 100%;
  height: auto;
}
#about .img {
  vertical-align: middle;
  border-style: none;
}
#about .about-extra {
  padding-top: 60px;
}
#about .about-extra h4 {
  font-weight: 600;
  font-size: 24px;
}
#about .p {
  padding: 0;
  margin: 0 0 30px 0;
}
#about .about-extra h4 {
  font-weight: 600;
  font-size: 24px;
}

#about .ready{
  margin-left: 2rem;
  font-size: 16px;
  
}

#about .about-extra ul {
  text-align: justify;
  font-size: 16px;
  padding-left: 2rem;
  list-style: circle;
}

</style>