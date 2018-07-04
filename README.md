# Iago1995.github.io
<!DOCTYPE html>
<html lang="en">
 <head>
   <meta name="viewport" content="width=device-width, initial scale=1.0">
   <meta http-equiv="X-UA-Compatible" content="ie=edge">
   <meta charset="UTF-8">
   <title>Iago Gabriel Ochner</title>
   <meta name="description" content="Sou aluno do SENAI SC,tenho 23 anos e estou em processo de reabilitação proficional.">
   <meta property="og:description" content="Sou aluno do SENAI SC,tenho 23 anos e estou em processo de reabilitação profissional.">
   <meta property="og:image" content="http://pre15.deviantart.net/6412/th/pre/i/2014/261/a/0/dick_dastardly____dick_vigarista__by_ikarow-d7zm0ld.jpg">
   <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
   <style type="text/css">
     body {
       background-image: url("http://img.elo7.com.br/product/original/8F0159/ceu-azul-270cm-x-2-0cm-paineis-fotograficos.jpg") ;
       font-family: monospace;
       text-align: center;
       color: #000000;
     }

     a:link, a:visited, a:active {
       text-decoration: none;
     }
     a:hover {
       text-decoration: none; 
       color:#000000;
     }
     h1 {
       font-size: 30px;
       color: #000000;
     }
     h2 {
       font-size: 15px;
       margin: 10px 0;
     }
     a {
       color: #FFFFFF;
       text-decoration: none;
     }
     section {
       margin: 15px 0;
     }
     .container {
       display: flex;
       align-items: center;
       justify-content: center;
       flex-direction: column;
       min-height: 95vh;
     }
     header {
       color: #000000;
     }
     header .photo img {
       border-radius: 50%;
     }
     header .basic-info .current-role {
       font-size: 20px;
     }
     header .sub-current-role {
       font-size: 30px;
       margin-bottom: 25px;
     }
     .contact {
       margin-top: 0;
     }
     .contact h2 {
       display: none;
     }
     .socials {
       margin: 15px 0;
     }
     .tags .tag {
       padding: 10px 10px;
       background-color: #A9A9A9;
       font-size: 15px;
       border-radius: 90px;
       display: inline-block;
       margin: 5px 0;
     }
     .companies img {
       margin: 10px;
       height: 25px;
     }
   </style>
 </head>

 <body>
   <main class="container">
     <header>
       <div class="photo">
         <img src="http://pre15.deviantart.net/6412/th/pre/i/2014/261/a/0/dick_dastardly____dick_vigarista__by_ikarow-d7zm0ld.jpg" alt="Iago Gabriel Ochner" width="139" height="142">
       </div>
       <div class="basic-info">
         <h1>Iago Gabriel Ochner</h1>
         <p class="current-role">Aluno Senai</p>
         <p class="sub-current-role">Sou aluno do SENAI SC,tenho 23 anos e estou em processo de reabilitação profissional.</p>
       </div>
     </header>
     <section class="contact">
       <h2 aria-hidden="true">Formação:</h2>
       <div>
         Email:
         <a href="mailto:iago_ochner@estudante.sc.senai.br">iago_ochner@estudante.sc.senai.br</a></div>
          <div>
         Github:
         <a href="https://github.com/Iago1995">@IagoOchner</a></div>
     </section>
     <section class="tags">
       <h2>Formação:</h2>
       <span class="tag">Ensino Médio Completo</span>
       <span class="tag">Cursando Técnico de Desenvolvimento de Sistemas</span>
     </section>
     <footer id="Date"></footer>
     <script language="javascript" type="text/javascript">
        function time(){
          var today=new Date();
          var  h=today.getHours();
          var d=today.getDate();
          var m=today.getMinutes();
          var s=today.getSeconds();
          var a=today.getFullYear();
          var mes=today.getMonth()+1;
          document.getElementById('Date').innerHTML= d+ '/' +mes+ '/' +a+' '+h+':' +m+ ':' +s;
        }
        setInterval(time,500);
      </script>
    </main>
  </body>
</html>
