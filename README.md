# Cypress | Configuração do Ambiente

 Página web criada para apresentar, de forma simples e organizada, os principais requisitos necessários para configurar um ambiente de desenvolvimento com **Cypress** no Windows.

 O projeto combina uma abordagem **editorial, técnica e humana**, utilizando uma identidade visual baseada em verde profundo, tipografia editorial e elementos inspirados em interfaces de teste, documentação e sistemas.

---

 ## Sobre o projeto

 Este projeto foi desenvolvido como um guia visual para quem está começando a trabalhar com testes automatizados utilizando Cypress.

 A página apresenta os principais recursos necessários para iniciar o ambiente:

 - Node.js
- Git Bash
- Visual Studio Code
- Cypress

 Cada recurso possui um link direcionando para sua respectiva página oficial ou documentação.

 Ao final da página, há um CTA direcionando para uma playlist com conteúdos sobre Cypress.

---

 ## Objetivo

 O objetivo é transformar uma lista simples de requisitos técnicos em uma experiência visual mais organizada e agradável.

 A interface foi pensada para equilibrar três características:

 **Editorial**

 Uso de tipografia serifada, contraste e composição para criar personalidade visual.

 **Técnica**

 Uso de elementos monoespaçados, status, labels e referências visuais a sistemas e testes.

 **Humana**

 Uso de cores orgânicas e uma composição mais sofisticada, evitando a estética genérica de interfaces de tecnologia.

---

 ## Identidade visual

 A identidade utiliza uma paleta baseada em tons de verde, marfim e dourado.

 | Cor | Hex | Uso |
| --- | --- | --- |
| Verde profundo | `#0F3D2E` | Cor estrutural |
| Verde-musgo | `#3F6F52` | Elementos secundários |
| Verde-sinal | `#8FE3B0` | Status e destaques |
| Dourado | `#C99A44` | Detalhes especiais |
| Marfim | `#F3EFE6` | Textos e áreas claras |
| Tinta | `#12201A` | Fundo e alto contraste |

### Regra visual

 > Menos sinal, mais significado.

 O verde-sinal é utilizado de forma pontual para representar confirmação, aprovação ou informação importante.

---

 ## Tipografia

 O projeto utiliza três famílias tipográficas:

 ### Newsreader

 Utilizada nos títulos e elementos editoriais.

 Sua característica serifada e o uso em itálico ajudam a criar personalidade e diferenciar a interface de uma estética puramente tecnológica.

 ### JetBrains Mono

 Utilizada em elementos técnicos, como:

 - Status
- Labels
- Metadados
- Botões
- Informações de sistema

 Exemplos:

```
STATUS: PASS
ENVIRONMENT / SETUP
REQ
```

 ### Manrope

 Utilizada no corpo da página e nas informações secundárias, garantindo legibilidade e equilíbrio entre os elementos editoriais e técnicos.

---

 ## Tecnologias utilizadas

 - HTML5
- CSS3
- Google Fonts
- CSS Grid
- CSS Flexbox
- Responsive Design

 Não são utilizados frameworks ou bibliotecas JavaScript.

---

 ## Estrutura do projeto

```
📁 setup-cypress/
│
├── 📁 .github/workflows/static.yml
│
├── index.html
│
├── 📁 css/
│   └── style.css
│
└── README.md
```

 ### `index.html`

 Contém a estrutura principal da página:

 - Header
- Apresentação
- Lista de requisitos
- Cards dos recursos
- CTA
- Footer

 ### `css/style.css`

 Responsável por toda a identidade visual e comportamento responsivo da página.

 Inclui:

 - Variáveis de cores
- Tipografia
- Layout
- Cards
- Estados de hover
- Responsividade
- Dark mode
- Acessibilidade para redução de movimento

---

 ## Recursos apresentados

 ### Node.js

 Utilizado para instalar, executar e gerenciar o Cypress e seus projetos.

 ### Git Bash

 Utilizado como terminal para executar comandos relacionados ao projeto.

 ### Visual Studio Code

 Editor utilizado para desenvolvimento e criação dos testes automatizados.

 ### Cypress

 Framework utilizado para criação, execução e depuração dos testes.

---

 ## Como executar

 Como o projeto utiliza apenas HTML e CSS, não é necessário instalar dependências.

 ### 1\. Clone o repositório

```
git clone <URL_DO_REPOSITORIO>
```

 ### 2\. Entre na pasta

```
cd cypress-config
```

 ### 3\. Abra o projeto

 Abra o arquivo `index.html` diretamente no navegador.

 Outra opção é utilizar uma extensão como **Live Server** no Visual Studio Code.

---

 ## Responsividade

 A interface foi desenvolvida para funcionar em diferentes tamanhos de tela.

 ### Desktop

 Os requisitos são apresentados em uma grade de duas colunas.

 ### Tablet

 Os cards se adaptam progressivamente ao espaço disponível.

 ### Mobile

 Os requisitos passam para uma única coluna, com redução dos elementos e ajustes de espaçamento para facilitar a leitura.

---

 ## Direção visual

 A interface foi construída para não seguir o padrão tradicional de uma landing page de tecnologia.

 Em vez de utilizar:

```
Preto + neon + glassmorphism
```

 a proposta utiliza:

```
Verde profundo
        +
Tipografia editorial
        +
Elementos técnicos
        +
Destaques pontuais
```

 O resultado busca transmitir:

 **credibilidade + precisão + personalidade**

---

 ## Princípios de design

 ### 01 — Hierarquia

 Cada informação possui um nível de importância visual.

 ### 02 — Contraste

 O contraste entre verde profundo, marfim e verde-sinal direciona a atenção sem sobrecarregar a interface.

 ### 03 — Sinalização

 Elementos como `STATUS: PASS` funcionam como indicadores de sistema e reforçam a linguagem técnica.

 ### 04 — Respiro

 Espaçamentos generosos separam as diferentes áreas da página e melhoram a leitura.

 ### 05 — Consistência

 A mesma identidade visual é aplicada aos diferentes componentes da interface.

---

 ## Links

- [Cypress](<https://www.cypress.io/>)
- [Documentação do Cypress](<https://docs.cypress.io/>)
- [Node.js](<https://nodejs.org/>)
- [Git](<https://git-scm.com/>)
- [Visual Studio Code](<https://code.visualstudio.com/>)

---

 ## Conteúdo sobre Cypress

 A página também disponibiliza uma playlist com conteúdos relacionados ao Cypress:

 https://www.youtube.com/playlist?list=PLeE4t9Tme9VKgzA9yTe6mtcZda1COlQL3

---

 ## Licença

 Este projeto pode ser utilizado para fins educacionais e de estudo.

 Consulte os respectivos projetos e serviços oficiais para informações sobre suas próprias licenças e termos de uso.

---

 ## Autor

 Projeto desenvolvido como parte dos estudos e práticas relacionados a **QA, testes automatizados, desenvolvimento web e Cypress**.

 **Hora do QA**