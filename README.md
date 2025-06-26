# Gerenciador_tarefas_web

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <title>Gerenciador de tarefas</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
</head>

<body>

    <main class="container my-5 d-flex flex-column align-items-center position-relative">
        <img src="img/Logomarca_gerenciador_de_tarefas.png" alt="Logo Gerenciador de Tarefas" width="120" height="104"
            class="position-absolute top-0 start-0 m-3">
        <div class="position-absolute" style="top: 120px; left: 24px;">
            <span style="font-size: 1rem; color: #333;">Gerenciador de tarefas</span>
            <hr style="border: none; border-top: 3px solid rgba(245, 145, 30, 0.932); width: 110px; margin: 4px 0 0 0;">
      <div class="mt-3 d-flex flex-row gap-4 justify-content-center">
                <div>
                    <span id="main-like" style="font-size: 1.3em; font-weight: bold;">0</span><br>
                    <span style="font-size: 0.85em;">Gerenciador</span>
                </div>
                <div>
                    <span id="main-dislike" style="font-size: 1.3em; font-weight: bold;">0</span><br>
                    <span style="font-size: 0.85em;">Tarefas</span>
                </div>
            </div>
        </div>

        <div class="d-flex mb-4 align-self-end gap-2" style="width: 260px;">
            <a href="#" class="btn w-50" style="background:orange; color: #fff;" data-bs-toggle="modal" data-bs-target="#loginModal">Entrar</a>
            <a href="cadastro.html" class="btn w-50"
                style="background:orange; color:#FFF; border:2px solid ;">Gerenciar</a>
        </div>

        <div class="d-flex justify-content-center w-100">
            <h2 class="text-center"
                style="font-weight: bold; color: #222; border: 1px solid #dee2e6; border-radius: 0.375rem 0.375rem 0 0; box-shadow: 0 0.125rem 0.25rem rgba(0,0,0,.075); padding: 12px 0; background: #fff; width: 27rem; margin-bottom: 0;">
                Tarefas
            </h2>
        </div>
        <div class="p-4 border rounded-top-0 mb-4" style="background-color: #fff; width: 27rem;">
            <div class="row justify-content-center">

                <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 1</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_1.jpg" class="card-img-top" alt="Tarefa gerenciada 1">
                        <div class="card-body text-center">
                            <ul id="gerenciadortarefas1" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                      <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 2</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_2.jpg" class="card-img-top" alt="Tarefa gerenciada 2">
                        <div class="card-body text-center">
                            <ul id="gerenciadortarefas2" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                            <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 3</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_3.jpg" class="card-img-top" alt="Tarefa gerenciada 3">
                        <div class="card-body text-center">
                            <ul id="gerenciadortarefas3" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                                  <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 4</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_4.jpg" class="card-img-top" alt="Tarefa gerenciada 4">
                        <div class="card-body text-center">
                            <ul id="gerenciadortarefas4" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                                        <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 5</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_5.jpg" class="card-img-top" alt="Tarefa gerenciada 5">
                        <div class="card-body text-center">
                            <ul id="gerenciadortarefas5" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                                              <div class="col-12 d-flex flex-column align-items-center mb-2">
                    <span class="mb-1" style="font-weight: bold; color: #000;">Tarefa gerenciada 6</span>
                    <div class="card mb-4" style="width: 27rem; position: relative;">
                        <img src="img/Tarefa_gerenciada_6.jpg" class="card-img-top" alt="Tarefa gerenciada 6">
                        <div class="card-body text-center">
                            <ul id="gereciadortarefas6" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>
                     
                    <ul id="gerenciadortarefas1" class="list-unstyled mt-2 text-start" style="font-size: 0.95em;"></ul>
                        </div>

                    <div class="card-footer bg-white border-0 p-0" style="position: relative;">

                        <div style="display: inline-block; padding: 10px 0 10px 10px;">
                                <button class="btn me-2" style="border:none;" onclick="incrementLike('gerenciador1')">
                                    <i class="bi bi-hand-thumbs-up"></i>
                                </button>
                                <span id="gerenciador1" style="font-weight:bold;">0</span>
                                <button class="btn ms-3" style="border:none;" onclick="incrementDislike('tarefas1')">
                                    <i class="bi bi-hand-thumbs-down"></i>
                                </button>
                                <span id="tarefas1" style="font-weight:bold;">0</span>
                            </div>

                            <div id="gerenciadorTarefas1" style="display:none; padding: 10px 10px 0 10px;">
                            <div class="form-floating">
                                <textarea class="form-control" placeholder="Deixe um comentário aqui" id="floatingTextarea1"
                                    style="height: 100px"></textarea>
                                <label for="floatingTextarea1">Tarefas gerenciadas</label>
                            </div>
                            <button class="btn btn-sm btn-primary mt-2 float-end"
                                onclick="submitFloatingComment('gerenciadortarefas1','floatingTextarea1','gerenciadorTarefas1')">Enviar</button>
                        </div>
                    </div>
                </div>

           </main>

           </body>

           <footer class="text-center py-4">
           <div class="container">
            <hr>
            <div class="row text-center py-3">
                <div class="col-md-4">
                    <strong>Gerenciador de tarefas</strong><br>
                </div>
                <div class="col-md-4">

                    <a href="gerenciador_de_tarefas@email.com" target="_blank" style="color:#fff; text-decoration:none; font-size:1.5em; margin:0 8px;">
                        <i class="bi bi-envelope-fill"></i>
                    </a>
                    <a href="https://www.instagram.com/gerenciadordetarefas" target="_blank" style="color:#fff; text-decoration:none; font-size:1.5em; margin:0 8px;">
                        <i class="bi bi-instagram"></i>
                    </a>
                    <a href="https://www.facebook.com/gerenciadordetarefas" target="_blank" style="color:#fff; text-decoration:none; font-size:1.5em; margin:0 8px;">
                        <i class="bi bi-facebook"></i>
                    </a>
                    <a href="https://wa.me/5511998123376" target="_blank" style="color:#fff; text-decoration:none; font-size:1.5em; margin:0 8px;">
                        <i class="bi bi-whatsapp"></i>
                    </a>
                </div>
                <div class="col-md-4">
                    <strong>Copyright-2025</strong><br>
                    
                </div>
            </div>
            <hr>
        </div>

    </footer>

    <div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="loginModalLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <form onsubmit="return loginRedirect(event)">
            <div class="modal-header">
              <h5 class="modal-title" id="loginModalLabel">Gerenciar</h5>
              <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Fechar"></button>
            </div>
            <div class="modal-body">
              <div class="mb-3">
                <label for="loginEmail" class="form-label">E-mail</label>
                <input type="email" class="form-control" id="loginEmail" required>
              </div>
              <div class="mb-3">
                <label for="loginSenha" class="form-label">Senha</label>
                <input type="password" class="form-control" id="loginSenha" required>
              </div>
            </div>
            <div class="modal-footer">
              <button type="submit" class="btn" style="background:#D97014; color:#FFF; width:50%;">Gerenciar</button>
            </div>
          </form>
        </div>
      </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous">
        </script>
    <script>

    </body>

</html>

