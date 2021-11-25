<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="login.css" />
    <!-- JavaScript Bundle with Popper -->
    <script
      src="https://code.jquery.com/jquery-3.5.1.min.js"
      integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
      crossorigin="anonymous"
    ></script>
    <script src="login.js"></script>
    <title>Acceso al Sistema</title>
  </head>

  <body>
    <div id="login">
      <div class="container">
      <div class=" text-center text-black text-uppercase shadow p-3 mb-5 fw-bold fs-2 bg-body rounded">A tiro de as LTDA</div>
      </div>
      <div class="container">
        <div
          id="login-row"
          class="row justify-content-center align-items-center"
        >
          <div id="login-column" class="col-md-6 ">
            <div id="login-box" class="col-md-12   rounded-3 border-light">
              <form id="login-form" class="form was-validated " >
                <h3 class="text-center" style="color:rgb(55, 10, 158)">Inicio de sesion</h3>
                <div class="form-floating mb-3 mt-3">
                 
                  <input
                    type="email"
                    name="useremail"
                    id="useremail"
                    class="form-control"
                    placeholder="name@example.com"
                    required
                  />
                 
                  <div class="invalid-feedback">Por favor complete este campo</div>
                  <label for="useremail">E-mail:</label><br />
                </div>
                <div class="form-floating mb-3 mt-3">
                
                  <input
                    type="password"
                    name="password"
                    id="password"
                    class="form-control"
                    placeholder="Ingrese contraseña"
                    required
                  />
                  
                  <div class="invalid-feedback">Por favor complete este campo</div>
                  <label for="password">Contraseña:</label><br />
                </div>
                
                <h6 class="text-center text-info "></h6>
                <div class="form-group text-center">
                  <input
                    type="submit"
                    name="submit"
                    class="btn btn-primary"
                    value="Ingresar"
                    onclick="login()"
                  />
                </div>
                <div class="form-group text-center">
                  <label for="remember-me" class="text-info">
                    <span style="color:black">No tienes una cuenta? </span>
                      <a href="registro.html" class="text-blue"
                        >Crea tu cuenta aqui</a>
                  
                  </label>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
