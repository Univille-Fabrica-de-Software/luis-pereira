# Decisões de Layout

## Introdução

Este documento registra as principais decisões de layout adotadas no desenvolvimento da landing page "Análise do Mercado de Tecnologia".

O objetivo é justificar escolhas visuais, estruturais e técnicas aplicadas na interface.

## Organização visual

A página foi organizada no formato de landing page, com seções verticais e navegação por âncoras.

Essa escolha facilita a leitura sequencial do conteúdo e permite que o usuário compreenda rapidamente:

- o objetivo da pesquisa;
- os dados analisados;
- as vagas locais e nacionais;
- as tecnologias observadas;
- as competências valorizadas;
- a análise final.

## Uso de Bootstrap

O Bootstrap foi utilizado para acelerar a construção da interface e garantir uma base responsiva.

Foram utilizados recursos como:

- `container`;
- `row` e `row-cols`;
- `col` e `col-lg`;
- `navbar` com `navbar-toggler` e `collapse`;
- `card` e `card-body`;
- classes de espaçamento (`mb-*`, `p-*`, `g-*`);
- classes de alinhamento (`text-center`, `justify-content-center`, `align-items-center`);
- classes de responsividade (`d-flex`, `flex-wrap`, breakpoints `lg`).


## Estrutura por seções

O conteúdo foi dividido em seções com a tag `section`.

Cada seção possui uma responsabilidade específica:

| Seção        | Finalidade                                         |
| ------------ | -------------------------------------------------- |
| Header       | Exibir logo e menu de navegação                    |
| Hero         | Apresentar o tema principal da página              |
| Pesquisa     | Explicar o levantamento realizado                  |
| Tecnologias  | Exibir tecnologias mais citadas                    |
| Vagas        | Apresentar vagas locais e nacionais                |
| Competências | Apresentar competências técnicas e comportamentais |
| Análise      | Sintetizar as exigências do mercado                |
| Footer       | Exibir informações finais da atividade             |

Essa divisão melhora a organização do código e facilita futuras manutenções.

## Cabeçalho

O cabeçalho utiliza uma `navbar` fixa no topo da página.

A logo do projeto foi carregada a partir do caminho:

```text
assets/images/univille.png
```

Todas as imagens e ícones ficam dentro de `assets/`

## Ícones

Os ícones das tecnologias mais citadas vêm do Font Awesome.

A escolha por ícones prontos evita a criação ou o armazenamento de imagens próprias

## Imagem do cabeçalho

A imagem exibida ao lado do título principal é aplicada por CSS, na classe `.hero-imagem`, como `background-image`.

A imagem é carregada de uma URL externa. 

## Paleta de cores

A identidade visual segue o verde com base na instituição `#026036`, aplicado em títulos, links da navbar, marcadores das listas de competências e no fundo do rodapé.

O fundo geral usa tons neutros (`#eae7e7` e `#f6f3f3`).

## Competências em duas colunas

As competências técnicas e comportamentais são apresentadas lado a lado, em duas colunas.

