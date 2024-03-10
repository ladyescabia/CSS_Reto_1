Completar los estilos con las siguientes indicaciones haciendo uso de unidades de medidas.

- La fuente por defecto del documento tiene que tener 16px.
- El h1 tiene que tener un tamaño de fuente el doble de lo que hay por defecto en el documento.
- El ancho máximo del main tiene que ser de 1000px.
- El padding del main y del footer tiene que ser el tamaño por defecto estipulado en el documento de 16px, pero utilizando una unidad relativa.
- El alto de la imagen tiene que ajustarse con unidades absolutas a lo mostrado en el ejemplo.

Os dejamos el CSS con los interrogantes que rellenar:

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-size: ?;
  font-family: sans-serif;
  color: white;
  background-color: black;
}

header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #333;
  padding: 1rem 2%;
}

h1 {
  font-size: ?;
  margin: 0;
}

img {
  height: ?;
}

main {
  max-width: ?;
  margin: 0 auto;
  padding: ?;
  text-align: left;
}

h2,
h3 {
  margin: 1rem 0;
}

ul {
  list-style: none;
}

li {
  margin: 0.5rem 0;
}

footer {
  background-color: #999;
  padding: ?;
  text-align: center;
}
