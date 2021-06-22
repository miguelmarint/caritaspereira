<template>
  <div>
    <Navbar />
    <Intro />
    <AboutUs />
    <Services />
    <Activities />
    <Donations />
    <WhyUs />
    <Documents />
    <VoluntaryForm />
    <Companies />
    <ContactUs />
    <Footer />
  </div>
</template>

<script>
import Navbar from "@/Layouts/Navbar";
import Intro from "./Intro";
import AboutUs from "./AboutUs";
import Services from "./Services";
import Activities from "./Activities";
import Donations from "./Donations";
import WhyUs from "./WhyUs";
import Documents from "./Documents";
import VoluntaryForm from "./VoluntaryForm";
import ContactUs from "./ContactUs";
import Footer from "@/Layouts/Footer";
import Companies from "./Companies";
export default {
  components: { Navbar, Intro, AboutUs, Services, Activities, Donations, WhyUs, Documents, VoluntaryForm, Companies, ContactUs, Footer },
};
</script>

<style scoped>
body {
  padding-top: 3.5rem;
  background: #fff;
}
</style>