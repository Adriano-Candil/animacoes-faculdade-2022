# animacoes-faculdade-2022
aprendendo animacoes com html e css

<!DOCTYPE html>
<html lang="pt-br">
<meta charset="utf-8">
    <head>
<style> 
div {
  width: 100px;
  height: 70px;
  background: #333;
  transition: width 1s;
  color:whitesmoke;
}

#div1 {transition-timing-function: linear;}
#div2 {transition-timing-function: ease;}
#div3 {transition-timing-function: ease-in;}
#div4 {transition-timing-function: ease-out ; transition-delay: 2s;} /* transition-delay para dar um delay na animação */
#div5 {transition-timing-function: ease-in-out;}

/* div:hover para a animação agir quando colocado o cursor do mouse sobre a animação , div:active para a animação agir quando clicar sobre a animação */
div:hover {
  width: 300px;
}
</style>
</head>
<body>

<h1>The transition-timing-function Property</h1>

<p>Hover over the div elements below, to see the different speed curves:</p>

    <div id="div1"><b>linear</b></div><br>
<div id="div2">ease</div><br>
<div id="div3">ease-in</div><br>
<div id="div4">ease-out</div><br>
<div id="div5">ease-in-out</div><br>

</body>
</html>
