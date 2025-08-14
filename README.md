### Funções Date, Math e String - Exercícios

-----

### Descrição

Este projeto é uma página web estática que serve como um conjunto de exercícios para demonstrar o uso de funções nativas do JavaScript, especificamente as classes `Date`, `Math` e `String`. Ele permite ao usuário interagir com a página para ver a data e hora atuais, realizar operações matemáticas simples e manipular strings.

O projeto inclui:

  * Visualização da data e hora atuais.
  * Geração de números aleatórios.
  * Cálculo do quadrado de um número.
  * Arredondamento de números.
  * Conversão de texto para maiúsculas.
  * Remoção de espaços extras de uma string.
  * Substituição de palavras em uma string.

-----

### Tecnologias Utilizadas

  * **HTML5**: Para a estrutura e marcação da página.
  * **CSS3**: Para estilização básica e layout.
  * **JavaScript (ES6+)**: Para toda a lógica e interatividade das funções.

-----

### Estrutura de Arquivos

A estrutura do projeto é a seguinte (considerando o link para o CSS e a pasta de imagens):

```
├── Exercicios/
│   └── css/
│       └── styles.css
├── img/
│   └── SENAI_São_Paulo_logo (1).png
└── index.html
```

-----

### Instalação e Uso

Como este é um projeto de página web estática com todo o código JavaScript embutido, a instalação é extremamente simples.

1.  **Clone o repositório** (se estiver hospedado em um):
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
2.  **Abra o arquivo `index.html`** em qualquer navegador web moderno (como Chrome, Firefox ou Edge).
3.  A página será carregada e você poderá interagir com os botões e campos de texto para testar as funcionalidades.

-----

### Funcionalidades do Código

#### Funções de Data e Hora

  * `dataAtual()`: Retorna a data atual no formato `dd/mm/aaaa`.
  * `horaAtual()`: Retorna a hora atual no formato `hh:mm:ss`. A exibição é atualizada a cada segundo.

#### Funções Matemáticas

  * `numeroAleatorio()`: Gera e retorna um número aleatório inteiro entre 50 e 100.
  * `quadrado(numero)`: Recebe um número e retorna seu quadrado.
  * `arredondar(numero)`: Recebe um número e o arredonda para o inteiro mais próximo.

#### Funções de String

  * `paraMaiusculas(texto)`: Converte uma string para letras maiúsculas.
  * `removerEspacos(texto)`: Remove espaços extras (múltiplos espaços e espaços no início/fim) de uma string.
  * `substituirPalavra(texto, palavraAntiga, palavraNova)`: Substitui todas as ocorrências de uma palavra em uma string por outra.

-----

### Créditos

Este projeto foi desenvolvido como um exercício no contexto de estudos no SENAI São Paulo.
