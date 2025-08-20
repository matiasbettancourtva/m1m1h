<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ejemplo Bootstrap</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MiLogo</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Empresa</a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Quiénes Somos</a></li>
              <li><a class="dropdown-item" href="#">Misión</a></li>
              <li><a class="dropdown-item" href="#">Visión</a></li>
            </ul>
          </li>
          <li class="nav-item"><a class="nav-link" href="#">Productos</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Servicios</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contacto</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contenido con Grid -->
  <div class="container my-5">
    <div class="row text-center">
      <div class="col-md-4">
        <div class="p-3 border bg-light">Columna 1</div>
      </div>
      <div class="col-md-4">
        <div class="p-3 border bg-light">Columna 2</div>
      </div>
      <div class="col-md-4">
        <div class="p-3 border bg-light">Columna 3</div>
      </div>
    </div>
  </div>

  <!-- Botón para abrir modal -->
  <div class="text-center mb-5">
    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#miModal">
      Abrir Modal
    </button>
  </div>

  <!-- Modal -->
  <div class="modal fade" id="miModal" tabindex="-1">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Título del Modal</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
        </div>
        <div class="modal-body">
          Este es el contenido del modal.
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cerrar</button>
          <button type="button" class="btn btn-primary">Guardar cambios</button>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center p-3 mt-5">
    &copy; 2025 Mi Empresa - Todos los derechos reservados
  </footer>
</body>
</html>
