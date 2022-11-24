# clocloclo

# COPIA APPLE

##################################################
##################################################
##################################################
#<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>iPhone 13 Pro</title>
    <link rel="stylesheet" href="css/styles.css" />
    <script src="js/scripts.js" defer></script>
  </head>
  <body>
    <header>
      <nav>
        <ul id="navbar">
          <li id="logo">
            <a href="#">
              <img src="img/logo_apple.svg" alt="Apple" />
            </a>
          </li>
          <li>
            <a href="#">Loja</a>
          </li>
          <li>
            <a href="#">Mac</a>
          </li>
          <li>
            <a href="#">iPad</a>
          </li>
          <li>
            <a href="#">iPhone</a>
          </li>
          <li>
            <a href="#">Watch</a>
          </li>
          <li>
            <a href="#">AirPods</a>
          </li>
          <li>
            <a href="#">Só na Apple</a>
          </li>
          <li>
            <a href="#">Acessórios</a>
          </li>
          <li>
            <a href="#">Suporte</a>
          </li>
        </ul>
      </nav>
      <div id="bottom-header">
        <div id="bottom-header-inner">
          <h3>iPhone 13 Pro</h3>
          <div id="bottom-header-links">
            <a href="#">Visão geral</a>
            <a href="#">Mudar para o iPhone</a>
            <a href="#">Especificações</a>
            <a href="#" class="btn">Comprar</a>
          </div>
        </div>
      </div>
    </header>
    <div id="ribbon">
      <p>
        Pague seu novo iPhone em até 12 parcelas ou economize 10% nos pagamentos
        à vista. <a href="#">Saiba mais</a>
      </p>
    </div>
    <main id="main-content">
      <h1 id="title">iPhone 13 Pro</h1>
      <p id="subtitle">É todo Pro.</p>
      <p id="description">
        O iPhone 13 Pro é uma enorme evolução. Ele traz uma rapidez absurda a
        tudo o que você faz e vem com novos recursos espetaculares para fotos e
        vídeos. Tudo em dois tamanhos.
      </p>
      <p id="price">A partir de R$ 9.499</p>
      <a href="#" class="btn">Comprar</a>
      <img id="product-image" src="img/iphone_green.jpg" alt="iPhone 13" />
      <div id="image-picker">
        <ul>
          <li id="green">
            <span class="color selected"></span>
            <span class="description">Verde-alpino</span>
          </li>
          <li id="silver">
            <span class="color"></span>
            <span class="description">Prateado</span>
          </li>
          <li id="golden">
            <span class="color"></span>
            <span class="description">Dourado</span>
          </li>
          <li id="grafite">
            <span class="color"></span>
            <span class="description">Grafite</span>
          </li>
          <li id="blue">
            <span class="color"></span>
            <span class="description">Azul-Sierra</span>
          </li>
        </ul>
      </div>
    </main>
  </body>
</html>



-------------------------------------------------
                     CSS 
-------------------------------------------------

/* Geral */
* {
  margin: 0;
  padding: 0;
  font-family: Verdana;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

/* Navbar */
header nav {
  background-color: #333;
}

#navbar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  font-size: 0.7rem;
  padding: 0 1rem;
  max-width: 1000px;
  margin: 0 auto;
}

#navbar a {
  color: #f5f5f7;
  transform: 4s;
}

#navbar a:hover {
  color: #fff;
}

#bottom-header {
  font-size: 0.8rem;
  padding: 1rem;
  border-bottom: 1px solid #ccc;
}

#bottom-header h3 {
  font-size: 1.2rem;
}

#bottom-header a {
  color: #333;
}

#bottom-header-inner {
  max-width: 1000px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#bottom-header-inner a {
  margin: 0 0.5rem;
}

#bottom-header-inner .btn,
.btn {
  background: #0071e3;
  border-radius: 10rem;
  padding: 0.4rem 1rem;
  color: #fff;
}

/* Conteúdo */
#ribbon {
  text-align: center;
  padding: 1rem;
  background-color: #f5f5f7;
  color: #1d1d1d;
  font-size: 0.8rem;
}

#ribbon a {
  color: #0071e3;
}

#main-content {
  text-align: center;
  color: #1d1d1d;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

#main-content #title {
  margin: 1rem;
  font-size: 1.2rem;
}

#main-content #subtitle {
  margin: 1rem;
  font-size: 1.2rem;
  font-size: 4rem;
  font-weight: bold;
}

#main-content #description {
  max-width: 600px;
  margin: 1rem auto;
  font-size: 1.1rem;
  line-height: 1.5rem;
}

#main-content #price {
  font-size: 1.3rem;
  color: #86868b;
  margin: 2rem;
}

#main-content .btn {
  font-size: 1.1rem;
  padding: 0.8rem 1.4rem;
  align-self: center;
}

#main-content #product-image {
  max-width: 1000px;
  margin: 3rem auto;
  opacity: 1;
  transition: 0.5s;
}

#main-content #product-image.changing {
  opacity: 0.5;
}

#image-picker {
  margin-bottom: 500px;
}

#image-picker ul {
  display: flex;
  justify-content: center;
}

#image-picker li {
  margin: 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  cursor: pointer;
}

#image-picker li .color {
  width: 2rem;
  height: 2rem;
  border-radius: 50%;
  box-shadow: 1px 1px 1px;
  border: 4px solid #fff;
  pointer-events: none;
}

#image-picker li .description {
  font-size: 0.7rem;
  color: #1d1d1d;
  margin-top: 0.6rem;
}

#green .color {
  background-color: #394c38;
}

#silver .color {
  background-color: #f1f2ed;
}

#golden .color {
  background-color: #fae7cf;
}

#grafite .color {
  background-color: #54524f;
}

#blue .color {
  background-color: #a7c1d9;
}

.selected {
  outline: 2px solid #43a1ff;
}

/* Mobile */
@media (max-width: 480px) {
  #navbar li {
    display: none;
  }

  #navbar #logo {
    display: flex;
  }

  #bottom-header-links a {
    display: none;
  }

  #bottom-header-links .btn {
    display: flex;
  }

  #main-content {
    padding: 2rem;
    overflow: hidden;
  }

  #main-content #subtitle {
    font-size: 3rem;
  }
}


##################################################
##################################################
##################################################





