# Top, Right, Bottom, Left

Propriedades como margin, padding e border permitem definirmos valores diferentes para cada um dos lados da caixa (box model).

div {
padding: 20px 40px;
margin: 30px 100px 60px 200px;
border-width: 30px 100px 100px;
outline-width: 10px;

}

div {
padding: top/bottom right/left;
margin: top right bottom left;
border-width: top right/left bottom;
outline-width: top right bottom left;
}
