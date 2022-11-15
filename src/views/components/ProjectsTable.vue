<template>
  <div class="card mb-4">
    <div class="card-header pb-0">
      <h6>Наши проекты</h6>
    </div>
    <div class="card-body px-0 pt-0 pb-2">
      <div class="table-responsive p-0">
        <table class="table align-items-center justify-content-center mb-0">
          <thead>
            <tr>
              <th class="text-uppercase text-secondary text-xxs font-weight-bolder opacity-7">Проект</th>
              <th class="text-uppercase text-secondary text-xxs font-weight-bolder opacity-7 ps-2">Бюджет</th>
              <th class="text-uppercase text-secondary text-xxs font-weight-bolder opacity-7 ps-2">Статус</th>
              <th class="text-uppercase text-secondary text-xxs font-weight-bolder text-center opacity-7 ps-2">
                Выполнено</th>
              <th></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="../../assets/img/small-logos/spotify.png"
                      class="avatar avatar-sm rounded-circle me-2" alt="spotify">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">Spotify</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$1000</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">В разработке</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">90%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-info" role="progressbar" aria-valuenow="60" aria-valuemin="0"
                        aria-valuemax="100" style="width: 90%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="../../assets/img/small-logos/soundcloud.png"
                      class="avatar avatar-sm rounded-circle me-2" alt="invision">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">SoundCloud</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$1500</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">В разработке</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">30%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-success" role="progressbar" aria-valuenow="100"
                        aria-valuemin="0" aria-valuemax="100" style="width: 30%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0" aria-haspopup="true" aria-expanded="false">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="../../assets/img/small-logos/vk.png" class="avatar avatar-sm rounded-circle me-2"
                      alt="jira">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">VK</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$50</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">Отмененно</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">10%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-danger" role="progressbar" aria-valuenow="30"
                        aria-valuemin="0" aria-valuemax="30" style="width: 10%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0" aria-haspopup="true" aria-expanded="false">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="../../assets/img/small-logos/instagram.png" class="avatar avatar-sm rounded-circle me-2"
                      alt="slack">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">Instagram</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$600</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">Выполненно</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">100%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-success" role="progressbar" aria-valuenow="0"
                        aria-valuemin="0" aria-valuemax="0" style="width: 100%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0" aria-haspopup="true" aria-expanded="false">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="https://demos.creative-tim.com/argon-dashboard/assets/img/small-logos/github.png"
                      class="avatar avatar-sm rounded-circle me-2" alt="webdev">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">GitHub</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$300</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">В разработке</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">80%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-info" role="progressbar" aria-valuenow="80" aria-valuemin="0"
                        aria-valuemax="80" style="width: 80%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0" aria-haspopup="true" aria-expanded="false">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
            <tr>
              <td>
                <div class="d-flex px-2">
                  <div>
                    <img src="../../assets/img/small-logos/twitter.png" class="avatar avatar-sm rounded-circle me-2"
                      alt="xd">
                  </div>
                  <div class="my-auto">
                    <h6 class="mb-0 text-sm">Twitter</h6>
                  </div>
                </div>
              </td>
              <td>
                <p class="text-sm font-weight-bold mb-0">$2000</p>
              </td>
              <td>
                <span class="text-xs font-weight-bold">В разработке</span>
              </td>
              <td class="align-middle text-center">
                <div class="d-flex align-items-center justify-content-center">
                  <span class="me-2 text-xs font-weight-bold">100%</span>
                  <div>
                    <div class="progress">
                      <div class="progress-bar bg-gradient-success" role="progressbar" aria-valuenow="100"
                        aria-valuemin="0" aria-valuemax="100" style="width: 10%;"></div>
                    </div>
                  </div>
                </div>
              </td>
              <td class="align-middle">
                <button class="btn btn-link text-secondary mb-0" aria-haspopup="true" aria-expanded="false">
                  <i class="fa fa-ellipsis-v text-xs" aria-hidden="true"></i>
                </button>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "projects-table"
}
</script>
