<template>
  <nav
    class="navbar navbar-expand-md navbar-light bg-white shadow-sm"
    :class="{ 'fixed-top': route().current() === 'landing' }"
  >
    <div class="container">
      <inertia-link class="navbar-brand" :href="route('landing')">
        <img
          id="brand"
          :src="asset('images/caritas-pereira.png')"
          class="img-fluid"
          alt="Caritas Pereira"
        />
      </inertia-link>

      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <!-- Right Side Of Navbar -->
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('intro')"
              class="btn btn-light nav-link "
            >
              {{ __("nav.home") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('about')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.about") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('services')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.services") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('activities')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.activities") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('why-us')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.why") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('documents')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.documents") }}
            </button>
          </li>
          <li class="nav-item">
            <button
              type="button"
              @click="scrollMeTo('contact')"
              class="btn btn-light nav-link"
            >
              {{ __("nav.contact") }}
            </button>
          </li>

          <language-selector></language-selector>

          <li v-if="!$page.props.user" class="nav-item">
            <inertia-link class="nav-link" :href="route('login')">{{
              __("nav.login")
            }}</inertia-link>
          </li>

          <li v-if="$page.props.user" class="nav-item dropdown">
            <a
              id="navbarDropdown"
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <i class="fas fa-user"></i>
            </a>
            <div
              class="dropdown-menu dropdown-menu-right"
              aria-labelledby="navbarDropdown"
            >
              <h6 class="dropdown-header">{{ $page.props.user.name }}</h6>
              <div class="dropdown-divider"></div>
              <jet-dropdown-link
                class="dropdown-item"
                :href="route('dashboard')"
              >
                {{ __("nav.dashboard") }}
              </jet-dropdown-link>
              <jet-dropdown-link
                class="dropdown-item"
                :href="route('profile.show')"
              >
                {{ __("nav.profile") }}
              </jet-dropdown-link>
              <form @submit.prevent="logout">
                <jet-dropdown-link as="button">{{
                  __("nav.logout")
                }}</jet-dropdown-link>
              </form>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import JetDropdownLink from "@/Jetstream/DropdownLink";
import LanguageSelector from "@/Shared/LanguageSelector";
export default {
  components: {
    JetDropdownLink,
    LanguageSelector,
  },
  methods: {
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
  },
};
</script>

<style scoped>
#brand {
  padding: 0;
  margin: 7px 0;
  max-width: 200px;
}

.navbar-nav .nav-item a,
.navbar-nav .nav-item button {
  display: block;
  position: relative;
  color: #0c0c0c;
  padding: 10px 15px;
  transition: 0.3s;
  font-size: 16px;
  font-family: "Montserrat", sans-serif;
  font-weight: 500;
}

.nav-link:hover{
  background-color: #799b9173;
  border-bottom-color: #025228;
  border-bottom-width: 3px;
  
}
</style>