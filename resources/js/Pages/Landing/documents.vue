<template>
  <div>
    <section id="documents" class="clearfix">
      <div class="container">
        <header class="section-header">
          <h3 class="section-title">Documentos</h3>
          <br>
          <p>
            La Fundación Cáritas de la Diocesis de Pereira (Risaralda) con Nit
            816004628; ha tramitado ante la DIAN su calificación en el Régimen
            Tributario Especial; por tal motivo, ponemos a disposición pública
            los siguientes documentos para que sean visualizados y descargados.
            En caso de cualquier inquietud puede escribirnos utilizando el
            formulario de contacto de este sitio web o a la dirección de correo
            electrónico: areaadministrativa@caritaspereira.org
          </p>
        </header>
        <div class="row">
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/informe-de-gestion.pdf">Informe de gestión</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/estados-financieros.pdf">Estados financieros</a>
            </div>
          </div> 
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/acta-junta-directiva.pdf">Acta junta directiva</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/camara-de-comercio.pdf">Certificado existencia</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/decreto-de-constitucion.pdf">Decreto constitución</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/certificado-RL-Antecedentes.pdf">Antecedentes judiciales</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/estatutos.pdf">Estatutos</a>
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6">
            <div id="documents-flters">
              <i class="far fa-file-pdf fa-2x"></i>
              <a href="/documents/certificado-RL-y-Revisor-Fiscal.pdf">Certificado del revisor <br> fiscal y representante <br> legal</a>
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
#documents {
  padding: 60px 0;
  box-shadow: 0px 0px 12px 0px rgb(0 0 0 / 10%);
  background: #025228;
}
.section-header h3 {
  font-size: 36px;
  color: #fff;
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
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
  background: #fff;
}
#documents i {
  padding: 0.5em;
  color: #025228;
}
#documents #documents-flters {
  padding: 0;
  margin: 5px 0 35px 0;
  list-style: none;
  text-align: left;
}
#documents #documents-flters a:hover{
  background: #025228;
  color: #fff;
}
#documents #documents-flters a {
  cursor: pointer;
  margin: 15px 15px 15px 0;
  display: inline-block;
  padding: 6px 20px;
  font-size: 12px;
  line-height: 20px;
  border-radius: 50px;
  text-transform: uppercase;
  margin-bottom: 5px;
  transition: all 0.3s ease-in-out;
}
#documents a {
  color: #000;
}
#documents i:hover {
  transform: scale(1.5);
}
</style>