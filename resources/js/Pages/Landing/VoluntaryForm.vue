<template>
  <div>
    <section id="why-us">
      <div class="container-fluid">
        <div class="section-header">
          <h3>¿Quieres ser voluntario?</h3>
          <p>Inscríbete aquí.</p>
        </div>

          <div class="col-sm">
            <div class="form">
              <div id="sendmessage">Your message has been sent. Thank you!</div>
              <div id="errormessage"></div>
              <form action="" method="post" role="form" class="contactForm">
                <div class="form-row">
                  <div class="form-group col-lg-6">
                    <input
                      type="text"
                      name="name"
                      class="form-control"
                      id="name"
                      placeholder="Nombre"
                      data-rule="minlen:4"
                      data-msg="Please enter at least 4 chars"
                    />
                    <div class="validation"></div>
                  </div>
                  <div class="form-group col-lg-6">
                    <input
                      type="email"
                      class="form-control"
                      name="email"
                      id="email"
                      placeholder="Correo electrónico"
                      data-rule="email"
                      data-msg="Please enter a valid email"
                    />
                    <div class="validation"></div>
                  </div>
                </div>
                <div class="form-group">
                  <input
                    type="text"
                    class="form-control"
                    name="subject"
                    id="subject"
                    placeholder="Asunto"
                    data-rule="minlen:4"
                    data-msg="Please enter at least 8 chars of subject"
                  />
                  <div class="validation"></div>
                </div>
                <div class="form-group">
                  <textarea
                    class="form-control"
                    name="message"
                    rows="5"
                    data-rule="required"
                    data-msg="Please write something for us"
                    placeholder="Mensaje"
                  ></textarea>
                  <div class="validation"></div>
                </div>
                <div class="text-center">
                  <button type="submit" title="Send Message">
                    Enviar mensaje
                  </button>
                </div>
              </form>
            </div>
          </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {};
</script>
<style  scoped>
#why-us {
  box-shadow: 0px 0px 12px 0px rgb(0 0 0 / 10%);
  padding: 60px 0;
  overflow: hidden;
  background: #799b9173;
}
container-fluid {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
#why-us .section-header {
  padding-bottom: 30px;
}
.section-header h3 {
  font-size: 40px;
  color: #000000;
  text-align: center;
  font-weight: 500;
  position: relative;
}
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
#why-us .info {
  color: #283d50;
}
#why-us .info i {
  font-size: 32px;
  color: #025228;
  float: left;
  line-height: 1;
}
#why-us .info p {
  padding: 0 0 10px 36px;
  line-height: 28px;
  font-size: 17px;
  font-family: "Arial Narrow";
}
#why-us .form #sendmessage {
  color: #007bff;
  border: 1px solid #007bff;
  display: none;
  text-align: center;
  padding: 15px;
  font-weight: 600;
  margin-bottom: 15px;
}
#why-us .form #errormessage {
  color: red;
  display: none;
  border: 1px solid red;
  text-align: center;
  padding: 15px;
  font-weight: 600;
  margin-bottom: 15px;
}
.form-row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -5px;
  margin-left: -5px;
}
.form-row > .col,
.form-row > [class*="col-"] {
  padding-right: 5px;
  padding-left: 5px;
}
#why-us .form input,
#why-us .form textarea {
  border-radius: 0;
  box-shadow: none;
  font-size: 14px;
}
#why-us .form .validation {
  color: red;
  display: none;
  margin: 0 0 20px;
  font-weight: 400;
  font-size: 13px;
}
.form-group {
  margin-bottom: 1rem;
}
.text-center {
  text-align: center !important;
}
#why-us .form button[type="submit"] {
  background: #025228;
  border: 0;
  border-radius: 20px;
  padding: 8px 30px;
  color: #fff;
  transition: 0.3s;
}
.section-header p {
  text-align: center;
  margin: auto;
  font-size: 15px;
  padding-bottom: 60px;
  color: #ffffff;
  width: 50%;
}
</style>