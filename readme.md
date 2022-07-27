<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário</title>
    <link rel="stylesheet"  href="style.css">

</head>
<body>
    
 <div class="box">
  <form action="">
   <fieldset>
     <legend><b>Formulário de Clientes</b></legend>
<br>
<div class="inputBox">
    <input type="text" name="nome" id="nome" class="inputUser" required>
    <label for="nome" class="labelInput">Nome Completo</label>
</div>
<br>
<div class="inputBox">
    <input type="text" name="email" id="email" class="inputUser" required>
    <label for="email" class="labelInput">Email</label>
    </div>
    <br>
    <div class="inputBox">
        <input type="tel" name="telefone" id="telefone" class="inputUser" required>
        <label for="telefone" class="labelInput">Telefone</label>
        </div>
        <p>Sexo</p>
        <input type="radio" id="feminino" name="genero" value="feminino" required>
        <label for="">Feminino</label>
        <br>
        <input type="radio" id="masculino" name="genero" value="masculino" required>
        <label for="">Masculino</label>
        <br>
        <input type="radio" id="outro" name="genero" value="outro" required>
        <label for="">Outro</label>
        <br><br>
        <div class="inputBox">
            <label for="data_nascimento"><b>Data de nascimento:</b></label>
            <input type="date" name="data_nascimento" id="data_nascimento" class="inputUser" required>
            </div>
            <br><br><br>

            <div class="inputBox">
                <input type="text" name="Cidade" id="cidade" class="inputUser" required>
                <label for="Cidade" class="labelInput">Cidade</label>
                </div>
                <br><br>
                 
                <div class="inputBox">
                    <input type="text" name="estado" id="estado" class="inputUser" required>
                    <label for="estado" class="labelInput">Estado</label>
                    </div>
                    <br><br>
                    
                    <div class="inputBox">
                        <input type="text" name="endereço" id="endereço" class="inputUser" required>
                        <label for="Endereço" class="labelInput">Endereço</label>
                        </div>
                        <br><br>

                       <input type="submit" name="submit" id="submit">

                     </fieldset>
                  </form>
               </div>

             </body>
           </html>