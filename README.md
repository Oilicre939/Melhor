<!DOCTYPE html>

<Html>
  <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>formulário</title>


<style>
  
body{
  background: green ;
}
h1{
  color: black;
  font-size: 30px;
  text-align: center;
  
}
h2{
  color: black;
  text-align: center;
}
input{
  text-align:center;
}
</style>
  </head>
<body>
  
  
    <a href="../index.html"> ir para a pasta voltar </a>
  
  <H1> Formulário </H1>
<h2>Criar primeiros passo para acessar um site</h2>
  <from>
    <!--Aqui coloquei e parate que diz que deve colocar nome...-->
    <label for="coloca_nome">Nome:</label>
    <!-- coloquei input tipo texto-->
<input id="colucar_nome" type="text" placeholder="Digite o seu nome" required><br><br>
<!--input tipo email-->
<label for="coloca_email">Email:</label>
<input id="colocar_email" type="email" placeholder="Digite seu email" required>
  <br><br>
  <!--input tipo palavra pass-->
  <laber for="colocar_pass">pass:</laber>
  <input id="coloca_pass" type="password" placeholder="digite seu palavra pass"required><br><br>
  <!--input tipo submeter-->
  <input type="submit" value=" clique aqui"><br><br><hr>
  
  <!--mais dois tipos de inputs abaixo-->
  
  <!--Usar input tipo rádio-->
<h2> Qual é a sua fruta favorita</h2>
<input type="radio" id="apple" name="fruta" value="Maça">
<!--ksksksksk-->
<label for="apple">maça</label><br>
<input type="radio" id="orange" value"laranja" nome="fruta">
<label for="orange">laranja</label><br>

 <input type="radio" id="mango" name="fruta" value="manga">
 <strong><label fro="mango">manga</label></strong> <br>
 <input type="radio" id="tomato" nome="fruta" value="tomate">
 <label for="tomato">tomate</label><br><br><hr>
 
 <!--usar input tipo checkboc-->
 <h2> Quais as coisas necessários</h2>
 
 <input type="checkbox" id="first" name="coisa" value="telefone">
 <label for="first">telefone</label><br>
 <input type="checkbox" id="segundo" name="coisa" value="sapato">
 <label for="segundo">sapato</label>
  <br>
   <input type="checkbox" id="terceiro" name="coisa" value="bola">
   <label for="terceiro">bola</label><br>
    <input type="checkbox" id="quarto" name="coisa" value="chinelo">
    <label for="quarto">chinelo</label><br>
     <input type="checkbox" id="quinto" name="coisa" value="cama">
     <label for="quinto">cama</label><br>
     
     <input type="checkbox" id="sexto" name="coisa" value="chinelo">
     <label for="sexto">chinelo</label><br><br><hr>
     <!--tag <select>-->
     <h2>Escolha suas cores</h2>
     <select name="cores" >
       <option disabled selected value="selecione uma cor">selecione um cor</option>
       <option value="azul">Azul</option>
       <option value="vermelho">vermelho</option>
       <option value="verde">verde</option>
       <optio value="castanho">castanho</optio></select><br><br> 
  </from> 
       <!--Usar tag <textarea>-->
       <h2>Escreva um comentário </h2>
       <textare placeholder="escreve seu comentário aqui" name="mensagem" rows="20" cols="50"> </textarea>
     
    </body>
</Html>
