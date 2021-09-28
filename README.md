# Criar-a-l-gica-por-tr-s-do-chute-com-if-else-if-e-else-Utilizar-a-fun-o-Math.random-do-JavaSc

var numeroSecreto = parseInt(Math.random() * 11);

function Chutar() {
  var elementoResultado = document.getElementById("resultado");
  var chute = parseInt(document.getElementById("valor").value);
  console.log(chute);
  if (chute == numeroSecreto) {
    elementoResultado.innerHTML = "VOCÊ ACERTOU!";
  } else if (chute > 10 || chute < 0) {
    lementoResultado.innerHTML = "VOCÊ DEVE DIGITAR UM NÚMERO DE 0 À 10.";
  } else {
    elementoResultado.innerHTML = "VOCÊ ERROU!";
  }
}
