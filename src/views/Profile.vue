<template>
  <main>
    
    <div class="container-fluid">
      <div class="d-flex gap-2  pt-4 h5-sm">
          <router-link to="/">
              График
          </router-link>  
          |
          <router-link to="/tables">
              Сотрудники
          </router-link>
          |
          <router-link to="/profile">
              Профиль
          </router-link>
      </div>
      <div
      class="page-header min-height-150"
      style="
          margin-right: -24px;
          margin-left: -34%;
        "
      >
        <span class=""></span>
      </div>
      <div class="card shadow-lg mt-n6">
        <div class="card-body p-3">
          <div class="row gx-4">
            <div class="col-auto">
              <div class="avatar avatar-xl position-relative">
                <img
                  src="../assets/img/team-1.jpg"
                  alt="profile_image"
                  class="shadow-sm w-100 border-radius-lg"
                />
              </div>
            </div>
            <div class="col-auto my-auto">
              <div class="h-100">
                <h5 class="mb-1">Вадим Басыгин</h5>
                <p class="mb-0 font-weight-bold text-sm">HR Менеджер</p>
              </div>
            </div>
            <div
              class="mx-auto mt-3 col-lg-4 col-md-6 my-sm-auto ms-sm-auto me-sm-0"
            >
              <div class="nav-wrapper position-relative end-0">
                
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="py-4 container-fluid">
      <div class="row">
        <div class="col-md-8">
          <div class="card">
            <div class="card-header   w">
              <div class="">
                <p class="">  </p>
              
              
              </div>
            </div>
            <div class="card-body">
              <p class="text-uppercase text-sm">Пользовательская информация</p>
              <div class="row">
                <div class="col-md-6">
                  <label for="example-text-input" class="form-control-label"
                    >Ник нейм</label
                  >
                  <Input type="text" value="vadim.basygin" />
                </div>
                <div class="col-md-6">
                  <label for="example-text-input" class="form-control-label"
                    >Email адресс</label
                  >
                  <Input type="email" value="vadim.basygin@uoggmk.com" />
                </div>
                <div class="col-md-6">
                  <label for="example-text-input" class="form-control-label"
                    >Имя</label
                  >
                  <input class="form-control" type="text" value="Вадим" />
                </div>
                <div class="col-md-6">
                  <label for="example-text-input" class="form-control-label"
                    >Фамилия</label
                  >
                  <Input type="text" value="Басыгин" />
                </div>
              </div>
              <hr class="horizontal dark" />
              <p class="text-uppercase text-sm">Контактная информация</p>
              <div class="row">
                <div class="col-md-12">
                  <label for="example-text-input" class="form-control-label"
                    >Адресс</label
                  >
                  <Input
                    type="text"
                    value="ул. Барташова д.18"
                  />
                </div>
                <div class="col-md-4">
                  <label for="example-text-input" class="form-control-label"
                    >Город</label
                  >
                  <Input type="text" value="Жлобин" />
                </div>
                <div class="col-md-4">
                  <label for="example-text-input" class="form-control-label"
                    >Страна</label
                  >
                  <Input type="text" value="Беларусь" />
                </div>
                <div class="col-md-4">
                  <label for="example-text-input" class="form-control-label"
                    >Почтовый индекс</label
                  >
                  <Input type="text" value="437300" />
                </div>
              </div>
              <hr class="horizontal dark" />
              <p class="text-uppercase text-sm">О мне</p>
              <div class="row">
                <div class="col-md-12">
                  <label for="example-text-input" class="form-control-label"
                    >О мне</label
                  >
                  <Input
                    type="text"
                    value="HR менеджер"
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <profile-card />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import setNavPills from "@/assets/js/nav-pills.js";
import setTooltip from "@/assets/js/tooltip.js";
import Input from "@/components/Input.vue";


const body = document.getElementsByTagName("body")[0];

export default {
  name: "profile",
  data() {
    return {
      showMenu: false
    };
  },
  components: {Input },

  mounted() {
    this.$store.state.isAbsolute = true;
    setNavPills();
    setTooltip();
  },
  beforeMount() {
    this.$store.state.imageLayout = "profile-overview";
    this.$store.state.showNavbar = false;
    this.$store.state.showFooter = true;
    this.$store.state.hideConfigButton = true;
    body.classList.add("profile-overview");
  },
  beforeUnmount() {
    this.$store.state.isAbsolute = false;
    this.$store.state.imageLayout = "default";
    this.$store.state.showNavbar = true;
    this.$store.state.showFooter = true;
    this.$store.state.hideConfigButton = false;
    body.classList.remove("profile-overview");
  }
};
</script>
