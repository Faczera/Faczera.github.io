<!-- Métodos de formulário> get ou post, para usar o comando é form: <form method="post" action="aula6.php"> -->
<!DOCTYPE html>
<html>
<head>
<title> Formulários </title>
 <meta charset="UTF-8">
 </head>
 <b><pre> <center> <font size=20> F O R M U L Á R I O </b> </pre> </center> </font>
 <body bgcolor=#87CEEB>
 <center> <img src="http://www.freeiconspng.com/uploads/intel-logo-png-6.png"> </center>
 <form method="post" action="form.html">
 <fieldset> <legend align="center" > <font size=20>  Trabalhe Conosco </legend> </font> 
 <p> <label for="nome">Nome:     <input type="text" placeholder="Nome completo" id="nome" size=55/> </p>
 <p> <label for="end"> Endereço: <input type="text" size=55 id=end/>
 Número: <input type="text" size= 2/></p>
 <p> <label for="cid"> Cidade:<input type="text" id="cid" size=55 placeholder="Selecione" list="cidades">
<datalist id="cidades">
<option value="Rio de Janeiro"/>
<option value="Niterói"/>
<option value="Itaboraí"/>
<option value="Nilópolis"/>
<option value="Campos Dos Goytacazes"/>
</datalist> 
 <p><label for="em"> Email:    <input type="email" size=55 id=em/></p>
 <!--<p> Senha: <input type="password" maxlength=8> -->
 <p> <label for="tel"> Telefone: <input type="text" size=55 id=tel/> </p> <!-- number -->
 <p> <label for="dn"> Data Nascimento <input type="date" size=55 id=dn/> </p>
  Sexo: <input type="radio" name="sexo" id="Masculino"/>Masculino <input type="radio" name="sexo" id="Feminino"/>Feminino <br>
 Cole aqui seu curriculo:<br>
  <textarea rows=10 col=80></textarea>
  
  
  
  <p><button> Enviar </button>
 
 
 </form>
 </fieldset>
 </body>
 </html>
 
