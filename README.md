<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Web</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    <style>
        html, body{
            height: 100%;
        }
        body{
            display: flex;
            align-items: center;
            background : rgba(112, 102, 255, 0.603);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="justify-content-center align-itens-conter row">
            <div class="col-4">
                <form class="formlogin">
                    <div class="text-center mb-3">
                        <h2>Formulário De Login</h2>
                    </div>
                    <div class="form-group">
                        <h5>Email:</h5>
                        <input type="text"  placeholder="informe o seu e-mail" class="form-control">
                    </div>
                    <div class="form-group">
                        <h5>Senha:</h5>
                        <input type="password" placeholder="informe o seu senha " class="form-control" />
                    </div>
                    <button class="btn btn-success btn-block btn-lg">ENTRAR</button>
                </form>
            </div>   
        </div>
    </div>
</body>
</html>
