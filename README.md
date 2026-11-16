# 🏁 Pit Wall — GP de São Paulo (Fórmula 1)

Landing page temática do **Grande Prêmio de São Paulo de Fórmula 1** no Autódromo de Interlagos, desenvolvida exclusivamente com **HTML5** e **CSS3** como atividade prática da disciplina de **Linguagem de Marcação (LIMA)**.

## 📋 Sobre o Projeto

O objetivo do desafio foi reproduzir uma interface moderna no estilo das transmissões oficiais da Fórmula 1, aplicando conceitos fundamentais de estruturação semântica, estilização avançada e design responsivo (Desktop e Mobile) sem o uso de JavaScript ou frameworks externos.

### ✨ Funcionalidades e Seções
* **Header (`topbar`)**: Barra de navegação superior com logotipo estilizado (`PITWALL`), links de âncora e botão de chamada para ação (*Comprar Ingresso*).
* **Hero Section & Zebra (`kerb`)**: Banner principal com título em destaque, dados técnicos do circuito de Interlagos (71 voltas, 4.309 km e 15 curvas), imagem de fundo sobreposta por gradiente com corte diagonal seco e faixa de zebra construída puramente com CSS.
* **01. Grid de Pilotos**: Cards responsivos exibindo número, nome e equipe dos pilotos (Charles Leclerc, Oscar Piastri, George Russell e Gabriel Bortoleto), utilizando variáveis CSS dinâmicas (`--team`) para identificar as cores de cada escuderia.
* **02. Classificação**: Área com campos de filtro visual (busca por piloto e seleção de equipe) e tabela estilizada com destaque para o líder do campeonato e barras laterais coloridas por equipe.
* **03. Ingressos**: Layout em duas colunas apresentando aviso de disponibilidade, tabela de preços por setor (Arquibancada A, Setor da Reta e Box VIP) e formulário completo de reserva (incluindo envio de foto para o telão e recado para o piloto).
* **Responsividade**: Adaptação completa para dispositivos móveis (`@media (max-width: 768px)`), reorganizando grids, empilhando formulários e habilitando rolagem horizontal na tabela de classificação.

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estruturação semântica (`header`, `nav`, `section`, `main`, `article`, `table`, `form`, `footer`).
* **CSS3**:
  * Variáveis CSS (`:root` e `var()`) para paleta de cores e identidade visual das equipes.
  * **Flexbox** e **CSS Grid** (`repeat(auto-fit, minmax(...))` e `form-grid`).
  * Gradientes lineares (`linear-gradient` com corte seco e `repeating-linear-gradient` para a zebra da pista).
  * Pseudo-classes e transições (`:hover`, `:focus`, `transform`).
  * **Media Queries** para responsividade.
* **Google Fonts**: Tipografia *Titillium Web*.

## 📁 Estrutura de Arquivos

```text
pit-wall/
├── index.html       # Estrutura principal da página
├── styles.css       # Estilização, layout e regras de responsividade
├── README.md        # Documentação do projeto
└── img/
    └── piloto.jpg   # Imagem de fundo da seção Hero
