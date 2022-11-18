<template>

    <div>

    </div>
    <nav class="navbar navbar-expand-sm navbar-dark">
        <div class="container">
          <button class="navbar-toggler ms-auto" type="button" data-bs-toggle="collapse" data-bs-target="#n_bar"
            aria-controls="navbarNavAltMarkup" aria-label="Toggle navigation">
            <div class="">
              <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-list"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
              </svg>
            </div>
          </button>
          <div class="collapse navbar-collapse" id="n_bar">
            <ul class="navbar-nav d-flex">
              <li class="nav-item active">
                <router-link to="/" class="nav-link" href="#">График</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/tables" class="nav-link" href="#">Сотрудники

                </router-link>
              </li>
              <li class="nav-item">
                <router-link to="/profile" class="nav-link" href="#">Профиль</router-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
</template>

<style>
@media (min-width: 768px) {
    .navbar-container {
        position: sticky;
        top: 0;
        overflow-y: auto;
        height: 100vh;
    }

    .navbar-container .navbar {
        align-items: flex-start;
        justify-content: flex-start;
        flex-wrap: nowrap;
        flex-direction: column;
        height: 100%;
    }

    .navbar-container .navbar-collapse {
        align-items: flex-start;
    }

    .navbar-container .nav {
        flex-direction: column;
        flex-wrap: nowrap;
    }

    .navbar-container .navbar-nav {
        flex-direction: column !important;
    }
}
</style>