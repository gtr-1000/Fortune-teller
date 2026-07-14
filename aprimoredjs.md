/*
// Selecionando os elementos que criamos no HTML
const fortuneButton = document.getElementById("fortune-btn");
const fortuneDisplay = document.getElementById("fortune-text");

// Agrupando suas previsões originais em um Array (Lista) profissional
const fortunes = [
  "Your cat will look very cuddly today.",
  "The weather will be nice tomorrow.",
  "Be cautious of your new neighbors.",
  "You will find a new hobby soon.",
  "It would be wise to avoid the color red today."
];

// Função responsável por sortear e exibir a sorte na tela
function tellFortune() {
  // Gera um índice aleatório correspondente à lista fortunes (entre 0 e 4)
  const randomIndex = Math.floor(Math.random() * fortunes.length);
  const selectedFortune = fortunes[randomIndex];

  // Remove o estilo de "placeholder" inicial
  fortuneDisplay.classList.remove("placeholder");
  
  // Força o reset da animação CSS removendo e recolocando a classe "revealed"
  fortuneDisplay.classList.remove("revealed");
  void fortuneDisplay.offsetWidth; // Truque para reiniciar a animação no navegador
  
  // Atualiza o texto na página e adiciona a animação de revelação
  fortuneDisplay.textContent = selectedFortune;
  fortuneDisplay.classList.add("revealed");
}

// Configura o ouvinte de eventos para disparar a função no clique do botão
fortuneButton.addEventListener("click", tellFortune);
*/
