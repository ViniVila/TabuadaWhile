📊 Painel de Tabuadas

Um projeto simples e funcional desenvolvido em HTML, CSS e JavaScript, que gera automaticamente as tabuadas do 1 ao 10 utilizando estruturas de repetição while.

Este projeto é ideal para treinar lógica de programação e manipulação do DOM.

🚀 Funcionalidades

✅ Gera automaticamente as tabuadas de 1 a 10
✅ Exibe os resultados dinamicamente na tela
✅ Utiliza estrutura de repetição while
✅ Manipula conteúdo HTML via JavaScript

🛠️ Tecnologias Utilizadas

HTML5 → Estrutura da página

CSS3 → Estilização básica

JavaScript → Lógica de programação

📂 Estrutura do Projeto
📁 painel-de-tabuadas
 └── index.html
🧠 Como Funciona

Ao clicar no botão "Gerar Tabuadas", a função abaixo é executada:

function gerarTabuadas()
🔹 Lógica aplicada:

Cria uma variável conteudo para armazenar o HTML gerado.

Utiliza um while externo para percorrer os números de 1 a 10.

Para cada número, cria outro while interno para calcular de 1 a 10.

Concatena os resultados em formato HTML.

Insere o conteúdo dentro da div com id resultado usando:

document.getElementById("resultado").innerHTML = conteudo;
📸 Resultado Esperado

Ao clicar no botão, o sistema exibirá:

Tabuada do 1
1 x 1 = 1
1 x 2 = 2
...
1 x 10 = 10

Tabuada do 2
2 x 1 = 2
...

Até a tabuada do 10.

🎯 Objetivo Educacional

Este projeto trabalha conceitos fundamentais como:

Estrutura de repetição while

Variáveis

Operações matemáticas

Manipulação do DOM

Eventos (onclick)

Concatenação de strings

🔥 Melhorias Futuras (Sugestões)

Permitir que o usuário escolha até qual número gerar

Adicionar campo de input

Melhorar o design com CSS mais moderno

Criar versão responsiva

Utilizar for ao invés de while

Separar CSS e JavaScript em arquivos externos

💻 Como Executar

Salve o arquivo como index.html

Abra no navegador

Clique em Gerar Tabuadas

Pronto ✅

👨‍💻 Autor

Projeto desenvolvido para prática de lógica de programação e JavaScript.
