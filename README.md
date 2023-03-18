# WebSite
echo "# WebSite" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/franneth/WebSite.git
 git push - u origen principal
<!DOCTYPE html>
<html>
<head>
  <title>Mi Página Web Innovadora</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <script src="script.js"></script>
</head>
<body>
  <header>
    <h1>Bienvenidos a mi página web innovadora</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Nosotros</a></li>
      <li><a href="#">Productos</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </nav>

  <section>
    <h2>Nuestros productos innovadores</h2>
    <p>Aquí puede encontrar información sobre nuestros productos innovadores y de alta tecnología.</p>
    <img src="https://via.placeholder.com/500x300" alt="imagen de producto">

    <button onclick="mostrarInformacion()">Más información</button>
    <p id="informacionAdicional" style="display: none;">Esta es más información sobre nuestros productos innovadores.</p>
  </section>

  <footer>
    <p>Derechos reservados 2023 - Mi página web innovadora</p>
  </footer>
</body>
</html>
