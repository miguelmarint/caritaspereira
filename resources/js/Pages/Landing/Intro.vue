<template>
  <div>
    <section id="intro" class="clearfix">
      <div class="container">
        <div class="slider">
          <button @click="prev" type="button" class="boton btn-left">
            <img src="/images/flecha-left.jpg" class="icone">
          </button>
            <div class="container-slides" :style="{transform: `translateX(${index}%)`, 
            transition: `${transition}` }">
              <img src="/images/tenequipo.jpg" class="img-slider">
              <img src="/images/responsabilidad-caritas.jpg" class="img-slider">
              <img src="/images/Pastoral.jpg" class="img-slider">
            </div>
          <button @click="next" type="button" class="boton btn-right">
            <img src="/images/flecha-right.jpg" class="icone">
          </button>
        </div>
        <div class="intro-info">
          <h2>
            Somos la labor <br /><span>social de la</span><br />Iglesia Católica
          </h2>
          <button type="button" @click="scrollMeTo('voluntary')" class=" btn btn btn-outline-dark mr-4">
            <strong>¿Quiere ser voluntario?</strong>
          </button>
          <button type="button" class="btn btn-outline-dark mr-4">
            <strong>!Quiero Donar¡</strong>
          </button>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import JetDropdownLink from "@/Jetstream/DropdownLink";
import LanguageSelector from "@/Shared/LanguageSelector";
import VoluntaryForm from './VoluntaryForm';

export default {
  components: {VoluntaryForm, JetDropdownLink, LanguageSelector,},
  name: 'Intro',
  data: function() {
    return {
      index: 0,
      transition: "transform 0.2s ease",
    }
  },
  methods: {
    next(){
      console.log(this.index);
      if(this.index === -200) {
        this.transition= "none";
        this.index = 0;
      } else{
        this.transition = "transform 0.2s ease";
        this.index -= 100;
      }
    },
    prev(){
      if(this.index === 0){
        this.transition = "none";
        this.index = -200;
      } else{
        this.transition = "transform 0.2s ease";
        this.index += 100;
      }
    },
        scrollMeTo(refName) {
      if (this.route().current() !== "landing") {
        this.$inertia.get(this.route("landing"), "", {
          onFinish: () => this.doScroll(refName),
        });
      } else {
        this.doScroll(refName);
      }
    },
    doScroll(refName) {
      var element = document.getElementById(`${refName}`);
      var top = element.offsetTop;
      window.scrollTo({
        top: top,
        left: 0,
        behavior: "smooth",
      });
    },
    logout() {
      this.$inertia.post(route("logout"));
    },
  }
}
</script>

<style scoped>
#intro {
  width: 100%;
  position: relative;
  background: url("/images/caritas1.png") center bottom no-repeat;
  background-size: cover;
  padding: 200px 0 120px 0;
}

#intro .intro-info {
  width: 50%;
  float: left;
}

#intro .intro-info h2 {
  color: #fff;
  margin-bottom: 40px;
  font-size: 48px;
  font-weight: 700;
}

#intro .btn-outline-dark:hover {
  background: #799b9173;
}

#intro .slider{
  width: 50%;
  height: 50vh;
  position: relative;
  overflow: hidden;
  background-color: #fff;
  float: right;
  border-radius: 10px;
}

#intro .container-slides {
  width: 100%;
  height: 100%;
  display: flex;
}

#intro .img-slider {
  width: 100%;
  height: auto;
  border-radius: 10px;

}

#intro .boton {
  outline: none;
  border: none;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  display: block;
  position: absolute;
  z-index: 1000;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #fff;
}

#intro .icone {
  width: 15px;
}

#intro .btn-left {
  top: 50%;
  left: 5px;
  transform: translateY(-50%);
}
#intro .btn-right {
  top: 50%;
  right: 5px;
  transform: translateY(-50%);
}

#intro .btn {
  font-size: 16px;
  color: rgb(224, 209, 209);
  border-width: 1.5px;
}


</style>