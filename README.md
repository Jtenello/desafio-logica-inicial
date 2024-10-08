Descrição Geral do Programa
O programa Classificador de Nível de Herói é uma aplicação web simples que permite ao usuário inserir o nome e a quantidade de experiência (XP) de um herói. Com base na XP fornecida, o programa classifica o herói em um nível específico e exibe uma mensagem correspondente com a cor do nível.

Estrutura do Código

HTML: Cria a estrutura visual da página, incluindo campos de entrada para nome e XP, um botão para classificar, e um parágrafo para mostrar o resultado.
CSS: Estiliza a página e os elementos, tornando-a visualmente atraente e fácil de usar.
JavaScript: Contém a lógica do programa, processando as entradas do usuário e determinando o nível do herói.
Funções e Lógica do Programa
Função classificarHeroi()
A função classificarHeroi() é a parte central do programa, responsável por processar a entrada do usuário e determinar o nível do herói com base na quantidade de XP.

Explicação da Função:
Obtenção dos Valores do Formulário:

let nome = document.getElementById("nome").value;: Captura o nome do herói inserido no campo de texto.
let experiencia = parseInt(document.getElementById("experiencia").value);: Captura a quantidade de XP e converte para um número inteiro.

Declaração das Variáveis:
let nivel;: Variável que armazenará o nível do herói.
let cor;: Variável que armazenará a cor correspondente ao nível do herói.

Estrutura de Decisão:
A função utiliza uma série de instruções if, else if e else para classificar o herói com base na XP:
Cada bloco verifica um intervalo de XP e atribui um nível e uma cor correspondente.
Por exemplo, se a XP for menor que 1000, o nível é "Ferro" e a cor é cinza.

Exibição do Resultado:
let resultadoElement = document.getElementById("resultado");: Captura o elemento HTML onde o resultado será exibido.
resultadoElement.innerText = ...;: Define o texto do elemento com a mensagem sobre o herói.
resultadoElement.style.color = cor;: Define a cor do texto com base no nível do herói.

Resumo do Funcionamento do Programa
O usuário insere o nome e a experiência do herói em um formulário.
Ao clicar no botão "Classificar", a função classificarHeroi() é chamada.
A função processa a entrada e determina o nível do herói com base na experiência.
O resultado é exibido na página, com o nome do herói e seu nível, em uma cor correspondente ao nível.
Esse programa fornece uma forma interativa e visual de classificar heróis com base em sua experiência, e pode ser expandido com mais funcionalidades, como a adição de novos níveis ou outras características dos heróis.
