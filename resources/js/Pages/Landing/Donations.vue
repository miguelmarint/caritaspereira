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

        <div class="slider">
          <div class="container-slides">
            <div class="dona-slider"></div>
            <div class="dona-slider"></div>
            <div class="dona-slider"></div>
          </div>
          <button @click="next" type="button" >Siguiente</button>
        </div>
        
      </div>
    </section>
  </div>
</template>
<script>
export default {
  components: {},
  name: 'Donations',
  data: function() {
    return {
      index: 0,
    }
  }
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

#donation .slider{
  width: 50%;
  height: 50vh;
  position: relative;
  overflow: hidden;
  background-color: #fff;
  border-radius: 10px;
}

#donation .container-slides {
  width: 100%;
  height: 100%;
  display: flex;
}

#donation .dona-slider {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

</style>