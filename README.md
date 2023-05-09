<html>
  <head>
<link rel="stylesheet" href="/css/MotorDeBuscaImg.css">
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  </head>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300;400;600;900&display=swap');

    @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700&display=swap');
    

  </style>
  <body>
    <style>
    
* {
box-sizing: border-box;
}
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300;400;600;900&display=swap');
  
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300;400;600;900&display=swap');
body {
  max-width: 1440px;
  margin: auto;
padding: 0;
font-family: 'Nunito', sans-serif;
font-weight: 400;
}
.container-header{
  position: fixed;
  max-width: 1440px;
z-index: 1;
width: 100%;
margin-bottom: 300px;
}
  .nav-title a{
      text-decoration: none;
      color: #06bbcc;
      font-weight: 600;
  }

.nav {
width: 100%;
background-color: #ffffff;
position: relative;
box-shadow: 0 0.5rem 1rem rgb(0 0 0 / 15%) !important;
}

.nav > .nav-header {
display: inline;
font-family: 'Nunito', sans-serif;
}

.nav > .nav-header > .nav-title {
display: inline-block;
font-size: 30px;
color: #06bbcc;
padding: 20px 20px;

}

.nav > .nav-btn {
display: none;
}

.nav > .nav-links {
display: inline;
float: right;
font-weight: 500;
font-size: 15px;
}
.nav > .nav-links > a:nth-child(2){
  color: #06bbcc;
}
.nav > .nav-links > a:nth-child(5){
  color: white;
  margin-right: 0;
  padding: 31px 41px;
  background-color: #06bbcc;
}
.nav > .nav-links > a:nth-child(5):hover{
  color: white;
  background-color: #029fad;
  transition: 0.5s ease;
}
.nav > .nav-links > a {
display: inline-block;
padding: 20px 0px;
margin-right: 30px;
text-decoration: none;
color: #000000;
}

.nav > .nav-links > a:hover {
color: #06bbcc;
transition:0.2s ease-out;
}

.nav > #nav-check {
display: none;
}

@media (max-width:930px) {
.nav > .nav-btn {
  display: inline-block;
  position: absolute;
  right: 10px;
  top: 10px;
}
.nav > .nav-links > a {
  display: inline-block;
  padding: 10px 20px;
  margin-right: 0px;
  font-weight: 600;
  text-decoration: none;
  color: #000000;
  font-weight: 600;
  font-size: 20px;
}
.nav > .nav-links > a:nth-child(2){
  color: #06bbcc;
} 
.nav > .nav-links > a:nth-child(5){
  color: rgb(0, 0, 0);
  margin-right: 0;
  padding: 10px 20px;
  background-color: white;
}
.nav > .nav-links > a:nth-child(5):hover{
color: #06bbcc;
margin-right: 0;
padding: 10px 20px;
background-color: white;
}
.nav > .nav-btn > label {
  display: inline-block;
  width: 50px;
  height: 50px;
  padding: 13px;
  background-color: #06bbcc;
}
.nav > .nav-btn > label:hover,.nav  #nav-check:checked ~ .nav-btn > label {
  background-color: rgba(0, 0, 0, 0.3);
}
.nav > .nav-btn > label > span {
  display: block;
  width: 25px;
  height: 10px;
  border-top: 2px solid #eee;
}
.nav > .nav-links {
  display: block;
  box-shadow: 0 0.5rem 1rem rgb(0 0 0 / 15%) !important;
  margin-bottom: 30px;
  width: 100%;
  background-color: #ffffff;
  color: black;
  height: 0px;
  transition: all 0.5s ease-in;
  overflow-y: hidden;
  left: 0px;
}
.nav > .nav-links > a {
  display: block;
  width: 100%;
}
.nav > #nav-check:not(:checked) ~ .nav-links {
  height: 0px;
}
.nav > #nav-check:checked ~ .nav-links {
  /* height: calc(100vh - 50px); */
  height: calc(300px - 50px);
  overflow-y: auto;

}
}


.Orientacoes{
  display: flex;
  width: 100%;
  flex-direction: column;
  text-align: center;
margin-top: 100px;
}
.Orientacoes a{
  text-decoration: none;
  color: #029fad;
}
.Orientacoes a:hover{
  color: #001eff;
  transition: 0.5s;
}
.Orientacoes p{
color: #000000;
}
.Orientacoes h1{
margin: 0;
margin-top: 50px;


}
/* Motor de busca */
/* Motor de busca */
/* Motor de busca */
/* Motor de busca */
/* Motor de busca */

.image-item h3{
  font-family: 'Nunito', sans-serif;
  font-size: 13px;
  text-align: center;
  color: black;
}
.image-item a{
  text-decoration: none;
}

body{max-width: 1440px;
margin:auto ;}
input[type="text"] {
  padding: 1em 1.8em;
  width: 50%;
  font-size: 16px;
  border: 1px solid #ddd;
  border-radius: 5px;
  margin-bottom: 10px;
}
button {
  position: relative;
  padding: 1em 1.8em;
  outline: none;
  border: 1px solid #303030;
  background: #212121;
  color: #f5f5f5;
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: 15px;
  overflow: hidden;
  transition: 0.2s;
  border-radius: 5px;
  cursor: pointer;
  font-weight: bold;
 }
 
 button:hover {
  box-shadow: 0 0 10px #ae00ff, 0 0 25px #001eff, 0 0 50px #ae00ff;
  transition-delay: 0.6s;
 }
 
 button span {
  position: absolute;
 }
 
 button span:nth-child(1) {
  top: 0;
  left: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(90deg, transparent, #ae00ff);
 }
 
 button:hover span:nth-child(1) {
  left: 100%;
  transition: 0.7s;
 }
 
 button span:nth-child(3) {
  bottom: 0;
  right: -100%;
  width: 100%;
  height: 2px;
  background: linear-gradient(90deg, transparent, #001eff);
 }
 
 button:hover span:nth-child(3) {
  right: 100%;
  transition: 0.7s;
  transition-delay: 0.35s;
 }
 
 button span:nth-child(2) {
  top: -100%;
  right: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(180deg, transparent, #ae00ff);
 }
 
 button:hover span:nth-child(2) {
  top: 100%;
  transition: 0.7s;
  transition-delay: 0.17s;
 }
 
 button span:nth-child(4) {
  bottom: -100%;
  left: 0;
  width: 2px;
  height: 100%;
  background: linear-gradient(360deg, transparent, #001eff);
 }
 
 button:hover span:nth-child(4) {
  bottom: 100%;
  transition: 0.7s;
  transition-delay: 0.52s;
 }
 
 button:active {
  background: #ae00af;
  background: linear-gradient(to top right, #ae00af, #001eff);
  color: #bfbfbf;
  box-shadow: 0 0 8px #ae00ff, 0 0 8px #001eff, 0 0 8px #ae00ff;
  transition: 0.1s;
 }
 
 button:active span:nth-child(1) 
 span:nth-child(2) 
 span:nth-child(2) 
 span:nth-child(2) {
  transition: none;
  transition-delay: none;
 }
 

.images {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}
.image-item {
  width: 200px;
  height: 300px;

}
.image-item img {
  width: 100%;

}
.Espaco-button-input{
text-align: center;
margin-top: 0px;
}


@media (max-width:550px){
  .nav > .nav-header > .nav-title{
    font-size: 17px;
  }

}
@media (max-width:450px){

  .image-item{
    width: 150px;
    height: 250px;
  }

}
    </style>
    <div class="container-header">
    <header data-aos="fade-right" style="transition: 2s;">
      <div class="nav">
          <input type="checkbox" id="nav-check">
          <div class="nav-header">
            <div class="nav-title"> <i class="fa-solid fa-book"></i><a href="https://educacao.andrattibrasil.com.br/unopar-rubiataba"> <b>Unopar Rubiataba</b> </a>
             
            </div>
          </div>
          <div class="nav-btn">
            <label for="nav-check">
              <span></span>
              <span></span>
              <span></span>
            </label>
          </div>
          
          <div class="nav-links">
            <a href="" target="_blank"></a>
            <a href="" target="_blank"></a>
            <a href="" target="_blank"></a>
            <a href="https://educacao.andrattibrasil.com.br/unopar-rubiataba">Voltar</a>
            <a href=""><b>Contato</b></a>
          </div>
        </div>
  </header>
</div>
<div class="Orientacoes">
  <h1>Tecnologos</h1>

  <a href="https://educacao.andrattibrasil.com.br/unopar-rubiataba-guias" style="padding: 10px 10px; background-color: #06bbcc; max-width: 200px; margin: auto; text-align: center; color: aliceblue;">Guias</a>

  <p>Procure sua Graduação de desejo através da barra de pesquisa abaixo, caso não encontre procure também em <a href="">Licenciatura</a> ou  <a href="https://educacao.andrattibrasil.com.br/unopar-rubiataba-bacharelado">Bacharelado</a>  
<br><br>
    Para saber melhor sobre o curso, basta clicar na imagem da graduação desejada</p>
</div>
    <div class="Espaco-button-input">
        
    <input placeholder="Pesquisar" type="text" id="searchInput" style="caret-color: red;">
    <button onclick="search()">  <span></span>
        <span></span>
        <span></span>
        <span></span> Pesquisar
    
    
    </button></div>
    <div class="Container-images" data-aos="fade-up">
    <div class="images">
      <div class="image-item">
        <a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$b3wo1br982a" alt="Agronegócio">
        <h3>Agronegócio</h3>
    </a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$0dqn6xpciq6i" alt="Análise e Desenvolvimento De Sistemas">
        <h3>Análise e Desenvolvimento De Sistemas</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$nawhyxfd4mf" alt="Arquitetura De Dados">
        <h3>Arquitetura De Dados</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$qzi672o2icd" alt="Blockchain, Criptomoedas e Finanças">
        <h3>Blockchain, Criptomoedas e Finanças</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$a52mz2792kb" alt="Cibersegurança">
        <h3>Cibersegurança</h3></a>
      </div>
      <div class="image-item">
        <a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$5tb6go5cf0t" alt="Ciência De Dados">
        <h3>Ciência De Dados</h3>
    </a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$rwr6kh12oyr" alt="Coaching e Desenvolvimento Humano">
        <h3>Coaching e Desenvolvimento Humano</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$d9r5bxzb4a" alt="Comércio Exterior">
        <h3>Comércio Exterior</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$1tk6q4rcjj5" alt="Computação Em Nuvem">
        <h3>Computação Em Nuvem</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$d2ve5r6z5pe" alt="Desenvolvimento Back-end">
        <h3>Desenvolvimento Back-end</h3></a>
      </div>
      <div class="image-item">
        <a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$sdl7o8xuqk" alt="Desenvolvimento Mobile">
        <h3>Desenvolvimento Mobile</h3>
    </a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$gjc6sq4u6rq" alt="Desenvolvimento Web">
        <h3>Desenvolvimento Web</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$zihywcu9gha" alt="Design De Moda">
        <h3>Design De Moda</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$p4beby7pjok" alt="Design Gráfico">
        <h3>Design Gráfico</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$lbldxok13xe" alt="Design De Interiores">
        <h3>Design De Interiores</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$ha60cfgiov5" alt="Devops">
        <h3>Devops</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$8qs8maf5mfa" alt="Empreendedorismo">
        <h3>Empreendedorismo</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$e9ii5h39swa" alt="Empreendedorismo E Novos Negócios">
        <h3>Empreendedorismo E Novos Negócios</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$nhatxe33ajp" alt="Eventos">
        <h3>Eventos</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$z6020pwf5db" alt="Fotografia">
        <h3>Fotografia</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$do6bdve1huk" alt="Gerontologia">
        <h3>Gerontologia</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$iq24tat387s" alt="Gestão Ambiental">
        <h3>Gestão Ambiental</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$i2urmuk6wz" alt="Gestão Comercial">
        <h3>Gestão Comercial</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$6ig6r8pswgi" alt="Gestão Da Inovação">
        <h3>Gestão Da Inovação</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$fhudvkn15io" alt="Gestão Da Produção Industrial">
        <h3>Gestão Da Produção Industrial</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$7m1nccniomn" alt="Gestão Da Qualidade">
        <h3>Gestão Da Qualidade</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$amb3q11gula" alt="Gestão Da Tecnologia Da Informação">
        <h3>Gestão Da Tecnologia Da Informação</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$i827p78uvrk" alt="Gestão De Cooperativas">
        <h3>Gestão De Cooperativas</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$cox1598xgo" alt="Gestão De Produto">
        <h3>Gestão De Produto</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$muy8z0ie3j" alt="Gestão De Recursos Humanos">
        <h3>Gestão De Recursos Humanos</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$civlxgqu6ug" alt="Gestão De Saúde Pública">
        <h3>Gestão De Saúde Pública</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$qkgchlgb9jo" alt="Gestão De Turismo">
        <h3>Gestão De Turismo</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$2adml07goml" alt="Gestão Financeira">
        <h3>Gestão Financeira</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$uno34hmcyt" alt="Gestão Hospitalar">
        <h3>Gestão Hospitalar</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$b8yh0fnnh2" alt="Gestão Portuária">
        <h3>Gestão Portuária</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$k5kgruidkm" alt="Gestão Pública">
        <h3>Gestão Pública</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$i1q4k9liyy" alt="Investigação De Mercado E Análise Dados">
        <h3>Investigação De Mercado E Análise Dados</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$yoi40wc2jh" alt="Investigação E Perícia Criminal">
        <h3>Investigação E Perícia Criminal</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$wzns7pwqutm" alt="Jogos Digitais">
        <h3>Jogos Digitais</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$2jd3hb1djsb" alt="Logística">
        <h3>Logística</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$f9fiv37nmjb" alt="Marketing">
        <h3>Marketing</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$4ol50ep3m6e" alt="Marketing Digital">
        <h3>Marketing Digital</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$7hnjnfhiuwg" alt="Mediação">
        <h3>Mediação</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$6pqisczw4y4" alt="Negócios Imobiliários">
        <h3>Negócios Imobiliários</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$38wtyvdvhg9" alt="Processos Gerenciais">
        <h3>Processos Gerenciais</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$fiwkk3oz7a" alt="Produção Cervejeira">
        <h3>Produção Cervejeira</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$gkmu7wp0sf" alt="Radiologia">
        <h3>Radiologia</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$0v7n8rc35qd" alt="Redes De Computadores">
        <h3>Redes De Computadores</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$uqu7022lcy9" alt="Secretariado">
        <h3>Secretariado</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$ug2tgdqly2c" alt="Segurança Pública">
        <h3>Segurança Pública (Apenas Concursados)</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$syvulwjz42p" alt="Serviços jurídicos Cartorários E Notariais">
        <h3>Serviços jurídicos Cartorários E Notariais</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$t2hxjwlwbk8" alt="Sistemas Para Internet">
        <h3>Sistemas Para Internet</h3></a>
      </div>
      <div class="image-item"><a href="">
        <img src="https://d335luupugsy2.cloudfront.net/cms/files/414721/1676403231/$2vwi15z5x6y" alt="Terapias Integrativas E Complementares">
        <h3>Terapias Integrativas E Complementares</h3></a>
      </div>
    </div>
  </div>
    <script>
      function search() {
        var input = document.getElementById("searchInput").value;
        var imageItems = document.getElementsByClassName("image-item");
        for (var i = 0; i < imageItems.length; i++) {
          if (imageItems[i].getElementsByTagName("img")[0].alt.toLowerCase().includes(input.toLowerCase())) {
            imageItems[i].style.display = "block";
          } else {
            imageItems[i].style.display = "none";
          }
        }
      }
    </script>
    
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init();
</script>
<script src="https://kit.fontawesome.com/abaec65dc3.js" crossorigin="anonymous"></script>
  </body>
</html>
