<!DOCTYPE html>
<!-- saved from url=(0035)http://127.0.0.1:5000/criar-receita -->
<html lang="pt-BR"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <title>
        
    Criar receita
 - Nutrigenius
    </title>
    <link rel="icon" type="image/x-icon" href="./Imagens/nutrigenius-colorido.svg">
    
    <link rel="stylesheet" type="text/css" href="./estilos.css">
    <link href="https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" >
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
<body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
        <img src="./Imagens/nutrigenius-vazado-preto.svg" width="40" alt="Logotipo da Nutrigenius">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
            <ul class="navbar-nav">
                
                    
                    <li class="nav-item">
                        <a class="nav-link" href="http://127.0.0.1:5000/dashboard">Receitas</a>
                    </li>
                    
                    <li class="nav-item">
                        <a class="nav-link" href="http://127.0.0.1:5000/logout">Sair</a>
                    </li>
                
            </ul>
        </div>
    </div>
</nav>
    <div class="m-4">
        
            
        
    </div>
    
    <form method="POST" action="http://127.0.0.1:5000/criar-receita" class="border p-4 m-4">
        <input id="csrf_token" name="csrf_token" type="hidden" value="ImJiMzBhMWFiNTVlNzQxMGQ3NTdkZGEzNWUxODE5NGMxZjNlMTQ1Njci.Zr1DlQ.BRnyJOqbNt1PkY_TYQec29Mx99U">
        <fieldset>
        <legend>Criar receita</legend>

        
            <div class="form-group">
                <table class="form-control mb-2 ingrediente" id="ingredientes-0"><tbody><tr><th><label for="ingredientes-0-ingrediente">Ingrediente</label></th><td><input id="ingredientes-0-ingrediente" name="ingredientes-0-ingrediente" type="text" value=""></td></tr></tbody></table><input id="ingredientes-0-csrf_token" name="ingredientes-0-csrf_token" type="hidden" value="ImJiMzBhMWFiNTVlNzQxMGQ3NTdkZGEzNWUxODE5NGMxZjNlMTQ1Njci.Zr1DlQ.BRnyJOqbNt1PkY_TYQec29Mx99U">
            </div>
        
            <div class="form-group">
                <table class="form-control mb-2 ingrediente" id="ingredientes-1"><tbody><tr><th><label for="ingredientes-1-ingrediente">Ingrediente</label></th><td><input id="ingredientes-1-ingrediente" name="ingredientes-1-ingrediente" type="text" value=""></td></tr></tbody></table><input id="ingredientes-1-csrf_token" name="ingredientes-1-csrf_token" type="hidden" value="ImJiMzBhMWFiNTVlNzQxMGQ3NTdkZGEzNWUxODE5NGMxZjNlMTQ1Njci.Zr1DlQ.BRnyJOqbNt1PkY_TYQec29Mx99U">
            </div>
        
            <div class="form-group">
                <table class="form-control mb-2 ingrediente" id="ingredientes-2"><tbody><tr><th><label for="ingredientes-2-ingrediente">Ingrediente</label></th><td><input id="ingredientes-2-ingrediente" name="ingredientes-2-ingrediente" type="text" value=""></td></tr></tbody></table><input id="ingredientes-2-csrf_token" name="ingredientes-2-csrf_token" type="hidden" value="ImJiMzBhMWFiNTVlNzQxMGQ3NTdkZGEzNWUxODE5NGMxZjNlMTQ1Njci.Zr1DlQ.BRnyJOqbNt1PkY_TYQec29Mx99U">
            </div>
        

        <div class="form-group">
            <label for="calorias">Calorias</label>
            <input class="form-control" id="calorias" min="0" name="calorias" required="" step="any" type="number" value="">
        </div>
        <input class="btn btn-primary mt-4" id="botao_submit_criar_receita" name="botao_submit_criar_receita" type="submit" value="Gerar receita">
    </fieldset>
    </form>

    <div class="d-flex px-4 mb-4 align-items-center gap-2">
        <a href="http://127.0.0.1:5000/criar-receita?num_entradas=2" class="btn btn-secondary"><i class="fa-solid fa-minus"></i></a>
        <p class="mb-0">3 ingredientes</p>
        <a href="http://127.0.0.1:5000/criar-receita?num_entradas=4" class="btn btn-secondary"><i class="fa-solid fa-plus"></i></a>
    </div>


    
        <div class="px-4 pb-4 pt-2">
            <hr>
            <h1>Salada Fitness de 1000 Calorias</h1>
            <p>1000 calorias</p>
            <h3>Ingredientes</h3>
            <ul>
                
                    <li>1 maço de salsinha fresca picada</li>
                
                    <li>100 ml de azeite de oliva</li>
                
                    <li>1 cebola média picada</li>
                
            </ul>
            <h3>Modo de preparo</h3>
            <ol>
                
                    <li>Lave bem a salsinha e pique finamente</li>
                
                    <li>Descasque e pique a cebola</li>
                
                    <li>Em uma tigela misture a salsinha picada a cebola picada e o azeite de oliva</li>
                
                    <li>Tempere a gosto com sal e pimenta</li>
                
                    <li>Sirva imediatamente</li>
                
            </ol>
            <h3>Rendimento</h3>
            <p>1 porção</p>
            <a href="http://127.0.0.1:5000/regerar-receita" class="btn btn-secondary"><i class="fa-solid fa-rotate-right"></i> Gerar a receita novamente</a>
            <a href="http://127.0.0.1:5000/salvar-receita" class="btn btn-success"><i class="fa-solid fa-floppy-disk"></i> Salvar receita</a>
        </div>
    
    <div class="container">
    <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 border-top">
        <p class="col-md-4 mb-0 text-muted">© 2024 <span class="brand">Nutrigenius</span></p>

        <a href="http://127.0.0.1:5000/" class="col-md-4 d-flex align-items-center justify-content-center mb-3 mb-md-0 me-md-auto link-dark text-decoration-none">
            <img src="./Imagens/nutrigenius-colorido.svg" style="width: 35px;" alt="Descrição da imagem">

        </a>

        <ul class="nav col-md-4 justify-content-end">
            <li class="nav-item"><a href="http://127.0.0.1:5000/dashboard" class="nav-link px-2 text-muted">Minhas receitas</a></li>
            <li class="nav-item"><a href="http://127.0.0.1:5000/criar-receita" class="nav-link px-2 text-muted">Criar receita</a></li>
        </ul>
    </footer>
</div>


</body></html>
