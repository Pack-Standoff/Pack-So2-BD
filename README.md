<!DOCTYPE html>  
  <html>  
  <head>  
      <meta charset="UTF-8">  
      <meta name="viewport" content="width=device-width, initial-scale=1.0">  
      <title>Pack Standoff 2</title>  
      <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap">  
      <style>  
          body {  
            margin: 0;  
            padding: 0;  
            background-color: #1C1C1C;  
            background-image: 
            font-family: Arial, sans-serif;} 
    .top-bar {  
      background-color: black;
      color: white;  
      padding: 5px;  
      text-align: center;  
      position: fixed;  
      top: 0;  
      width: 100%;  
      z-index: 3;
    }  
    .top-bar img.left-corner {  
      position: absolute;  
      center: fixed;
      top: 8px;  
      width: 180px;  
      height: 35px;
      left: 50%;
      transform: translateX(-50%); 
     }  
    .logo {
      position: fixed;
      top: 10%; 
      left: 50%;
      transform: translate(-50%, -50%);
      width: 100px; 
      height: auto; 
      z-index: 1; 
    }
    .square {  
      text-align: center;  
      margin-top: 10%;  
    }  
    .button-ver-container {  
      position: absolute;  
      top: 80%;  
      left: 30%;  
      transform: translate(-50%, -50%);  
      z-index: 2;  
    }  
    .button-ver {  
      background-image: url('http://tinyurl.com/2s44u2eu');  
      background-size: cover;  
      background-position: center;  
      background-color: transparent;  
      color: white;  
      padding: 1px 40px;  
      border: none;  
      cursor: pointer;  
      font-family: 'Bebas Neue', sans-serif;  
      font-size: 16px;  
    }  
    .button-see-container {  
      position: absolute;  
      top: 75%;  
      left: 72%;  
      transform: translate(-50%, -50%);  
      z-index: 2;  
    }  
    .button-see {  
      background-image: url('http://tinyurl.com/2s44u2eu');  
      background-size: cover;  
      background-position: center;  
      background-color: transparent;  
      color: white;  
      padding: 1px 40px;  
      border: none;  
      cursor: pointer;  
      font-family: 'Bebas Neue', sans-serif;  
      font-size: 16px;  
    }  
    .button-escutar-container {  
      position: absolute;  
      top: 75%;  
      left: 29%;  
      transform: translate(-50%, -50%);  
      z-index: 1;  
    }  
    .button-escutar {  
      background-image: url('http://tinyurl.com/2s44u2eu');  
      background-size: cover;  
      background-position: center;  
      background-color: transparent;  
      color: white;  
      padding: 2px 32px;  
      border: none;  
      cursor: pointer;  
      font-family: 'Bebas Neue', sans-serif;  
      font-size: 16px;  
    }  
    .scrolling-wrapper {
      display: flex;
      overflow-x: auto;
      justify-content: center;
    }
    button {
      padding: 10px;
      margin-right: 0px;
      background-color: transparent;
      border: none;
      color: white;
      cursor: pointer;}
              
    button:hover {
      background-color: transparent;
      background-image: url("http://tinyurl.com/mwtbsvay");
    }
    </style>  
</head>  
  <body>  
    <div class="top-bar">
      <div class="scrolling-wrapper">
      <button onclick="redirecionarParaHome()">Home</button>
      <button onclick="redirecionarParaConteudo()">Conteúdo</button>
      <button onclick="redirecionarParaTabela()">Tabela</button>
      <button onclick="redirecionarParaSoundtrack()">Soundtracks</button>
      <button onclick="redirecionarParaAmostra()">Amostra</button>
      </div>
  </div>
    <div class="square" style="margin-top: 60px;">  
      <div style="width: 100%; height: 100%; background-color: transparent; position: relative; margin-bottom: 10px;">  
         <img src="http://tinyurl.com/zeduk4ye" alt="imagem" style="width: 70%; height: 70%; object-fit: cover;" oncontextmenu="return false;"></div>  
  
      <div class="square" style="margin-top: 0px;">  
         <div style="width: 100%; height: 100%; background-color: transparent; position: relative; margin-bottom: 18px;">  
         <img src="http://tinyurl.com/3uhtnb7p" alt="imagem" style="width: 100%; height: 100%; object-fit: cover;" oncontextmenu="return false;"></div>  
  
         <div style="width: 100%; height: 100%; background-color: transparent; position: relative; margin-bottom: 18px;">  
         <img id="imagemAleatoria" src="http://tinyurl.com/56u6d7cu" alt="imagem" style="width: 100%; height: 100%; object-fit: cover;" oncontextmenu="return false;">
           <div class="button-ver-container">  
         <button class="button-ver" onclick="abrirNovaPaginaVer()">Ver</button></div></div>  
  
         <div style="width: 100%; height: 100%; background-color: transparent; position: relative; margin-bottom: 18px;">  
         <img src="http://tinyurl.com/2za3uhp3" alt="em breve" style="width: 100%; height: 100%; object-fit: cover;" oncontextmenu="return false;"> 
         <div class="button-see-container">  
         <button class="button-see" onclick="abrirNovaPaginaTabela()">Ver</button></div></div> 
  
         <div style="width: 100%; height: 100%; background-color: transparent; position: relative; margin-bottom: 18px;">  
         <img src="http://tinyurl.com/3tmxzh9f" alt="em breve" style="width: 100%; height: 100%; object-fit: cover;" oncontextmenu="return false;">  
         <div class="button-escutar-container">  
         <button class="button-escutar" onclick="abrirNovaPaginaEscutar()">Escutar</button></div></div></div>  
  
 </div> 
<script>
    function abrirNovaPaginaVer() {
      window.location.href = "https://pack-standoff.vercel.app/Conte%C3%BAdo.html";
    }

    function abrirNovaPaginaTabela() {
      window.location.href = "https://pack-standoff.vercel.app/Tabela.html";
    }

    function abrirNovaPaginaEscutar() {
      window.location.href = "https://pack-standoff.vercel.app/Pack%20Soundtrack.html";
    }  
    function redirecionarParaConteudo() {
    window.location.href = "https://pack-standoff.vercel.app/Conte%C3%BAdo.html";
    }    
    function redirecionarParaTabela() {
      window.location.href = "https://pack-standoff.vercel.app/Tabela.html";
    }
    
    function redirecionarParaSoundtrack() {
    window.location.href = "https://pack-standoff.vercel.app/Pack%20Soundtrack.html";
    }
    function redirecionarParaAmostra() {
    window.location.href = "https://pack-standoff.vercel.app/Login.html";
    }
      function carregarImagemAleatoria() {
            var imagemAleatoriaElement = document.getElementById('imagemAleatoria');
            imagemAleatoriaElement.src = imagesArray[Math.floor(Math.random() * imagesArray.length)];
        }

        var imagesArray = [
            "http://tinyurl.com/56u6d7cu",  // URL da Imagem 1
            "http://tinyurl.com/4vs2mre6"   // URL da Imagem 2
        ];

        carregarImagemAleatoria();
    
    
</script>
  </body>  
</html>
