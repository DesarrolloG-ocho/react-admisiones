<template>
<div class="Login">
  <div class="container position-sticky z-index-sticky top-0">
    <div class="row"> 
      <div class="col-12">
      </div>
    </div>
  </div>
  <main class="main-content  mt-0">
    <section>
      <div class="page-header min-vh-100">
        <div class="container">
          <div class="row">
            <div class="col-xl-4 col-lg-5 col-md-7 d-flex flex-column mx-lg-0 mx-auto">
              <div class="card card-plain">
                <div class="card-header pb-0 text-start">
                  <div class="text-center">
                    <img 
                    src="https://www.ospedale.com.co//wp-content/uploads/2021/07/cropped-Logo-G-Ocho-full.png"
                    class="img-fluid"
                    width="60"
                    />
                    <h4 class="font-weight-bolder mt-3">Iniciar Sesiòn</h4>
                  </div>
                  <p class="mb-0 mt-3">
                    Ingrese su usuario y contraseña para iniciar sesión
                  </p>
                </div>
                <div class="card-body">
                 <form role="form">
                  <div class="mb-3">
                    <input
                      type="text"
                      class="form-control form-control-lg"
                      placeholder="Usuario"
                      aria-label="Usuario"
                    />
                  </div>
                  <div class="mb-3">
                    <input
                      type="password"
                      class="form-control form-control-lg"
                      placeholder="Contraseña"
                      aria-label="Contraseña"
                    />
                  </div>
                  <div class="form-check form-switch">
                    <input
                      class="form-check-input"
                      type="checkbox"
                      id="rememberMe"
                    />
                    <label
                      class="form-check-label"
                      for="rememberMe"
                    > Recordarme
                    </label>
                  </div>
                  <div class="text-center">
                    <button
                      type="button"
                      class="btn btn-lg btn-primary btn-lg w-100 mt-4 mb-0"
                    >
                    Ingresar
                    </button>
                  </div>
                </form>
              </div>
              <div class="card-footer text-center pt-0 px-lg-2 px-1">
                <p class="mb-4 text-sm mx-auto">
                  ¿No tienes cuenta?
                  <a
                    href="javascript:;"
                    class="text-primary text-gradient font-weight-bold"
                  >
                  Inscribirse
                  </a>
                </p>
              </div>
            </div>
          </div>
          <div class="col-6 d-lg-flex d-none h-100 my-auto pe-0 position-absolute top-0 end-0 text-center justify-content-center flex-column">
            <div
              class="position-relative bg-gradient-primary h-100 m-3 px-7 border-radius-lg d-flex flex-column justify-content-center overflow-hidden"
              style="background-image: url('https://www.medicadiz.co/wp-content/uploads/2018/04/servicios.jpg');
              background-size: cover;"
            >
              <span class="mask bg-gradient-primary opacity-6"></span>
              <h4 class="mt-5 text-white font-weight-bolder position-relative">
                HIS - Hosvital
              </h4>
              <p class="text-white position-relative">
                The more effortless the writing looks, the more effort the writer
                actually put into the process.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>
</div>
</template>

