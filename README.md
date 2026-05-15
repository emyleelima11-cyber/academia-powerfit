<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

  <title>Academia PowerFit</title>
</head>
<body>


<!-- MENU -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">PowerFit</a>
    
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="menu">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#planos">Planos</a></li>
        <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li>
      </ul>
    </div>
  </div>
</nav>
 

<!-- HOME -->
<section id="home" class="bg-light text-center p-5">
  <div class="container">
    
    <h1 style="font-family: 'Poppins', sans-serif; font-weight: 700; font-size: 3rem;">
      Bem-vindo à PowerFit 💪
    </h1>

    <p>Sua melhor versão começa aqui!</p>

    <!-- IMAGEM -->
    <img src="https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=1200"
         class="img-fluid rounded shadow mt-4"
         alt="Academia PowerFit"
         style="max-height: 350px; width: 80%; object-fit: cover;">
         
  </div>
</section>


<!-- PLANOS -->
<section id="planos" class="p-5">
  <div class="container">
    <h2 class="text-center mb-4">Nossos Planos</h2>

    <div class="row">

      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5>Plano Básico</h5>
            <p>R$ 59,90/mês</p>
            <p>Acesso à academia</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5>Plano Intermediário</h5>
            <p>R$ 79,90/mês</p>
            <p>Acesso + Aulas</p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card text-center">
          <div class="card-body">
            <h5>Plano Premium</h5>
            <p>R$ 99,90/mês</p>
            <p>Tudo incluso + Personal</p>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- CONTATO -->
<section id="contato" class="bg-dark text-white text-center p-5">
  <div class="container">
    <h2>Contato</h2>
    <p>Telefone: (47) 99999-9999</p>
    <p>Email: contato@powerfit.com</p>
  </div>
</section>

<!-- RODAPÉ -->
<footer class="bg-black text-white text-center p-3">
  <p>© 2026 Academia PowerFit</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
