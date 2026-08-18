# Registro de Testes

## Introdução

Este documento registra os testes manuais realizados na landing page "Análise do Mercado de Tecnologia".

O objetivo é verificar se a página abre corretamente, se os recursos visuais são carregados, se a navegação funciona e se o layout responde adequadamente em diferentes tamanhos de tela.

## Ambiente de teste

| Item                   | Informação                 |
| ---------------------- | -------------------------- |
| Sistema operacional    | Windows 11 Pro             |
| Navegador utilizado    | Chrome / Edge              |
| Editor de código       | VS Code                    |
| Forma de execução      | Arquivo local              |
| Data do teste          | 18/08/2026                 |
| Responsável pelo teste | Luis Guilherme Pereira     |

## Teste 1 - Abertura da página

| Verificação                   | Resultado esperado                                      | Status    |
| ----------------------------- | ------------------------------------------------------- | --------- |
| Abrir o arquivo `index.html`  | A página deve abrir no navegador sem erro               | Validado  |
| Carregar o título da aba      | A aba deve exibir "Análise do Mercado de Tecnologia"    | Validado  |
| Carregar o conteúdo principal | O título e a descrição inicial devem aparecer           | Validado  |
| Carregar o Bootstrap          | Layout deve aparecer organizado em grid, cards e navbar | Validado  |
| Carregar o CSS próprio        | Ajustes de espaçamento, logo e efeitos devem funcionar  | Validado  |
| Carregar o Font Awesome       | Os ícones das tecnologias devem aparecer nos cards      | Validado  |

## Teste 2 - Logo e favicon

| Verificação                         | Resultado esperado                                        | Status    |
| ----------------------------------- | --------------------------------------------------------- | --------- |
| Exibir a logo no cabeçalho          | A imagem `assets/images/univille.png` deve aparecer       | Validado  |
| Verificar texto alternativo da logo | A imagem deve possuir atributo `alt`                      | Validado  |
| Exibir favicon na aba               | O ícone deve aparecer na aba do navegador                 | Validado  |
| Conferir caminhos dos ícones        | Os caminhos devem apontar para `assets/icons/favicon_io/` | Validado  |

## Teste 3 - Navegação interna

| Link do menu | Destino esperado                                      | Status    |
| ------------ | ----------------------------------------------------- | --------- |
| Início       | Deve navegar para a seção inicial                     | Validado  |
| Pesquisa     | Deve navegar para a seção de apresentação da pesquisa | Validado  |
| Tecnologias  | Deve navegar para a seção de tecnologias mais citadas | Validado  |
| Vagas        | Deve navegar para a seção de vagas analisadas         | Validado  |
| Competências | Deve navegar para a seção de competências observadas  | Validado  |
| Conclusão    | Deve navegar para a seção de análise final            | Validado  |

## Teste 4 - Conteúdo obrigatório

| Conteúdo                 | Resultado esperado                                      | Status    |
| ------------------------ | ------------------------------------------------------- | --------- |
| Cabeçalho                | Deve conter logo e menu                                 | Validado  |
| Apresentação inicial     | Deve conter título, descrição e autoria                 | Validado  |
| Apresentação da pesquisa | Deve explicar o levantamento realizado                  | Validado  |
| Vagas locais             | Deve apresentar 4 vagas locais                          | Validado  |
| Vagas nacionais          | Deve apresentar 4 vagas nacionais                       | Validado  |
| Tecnologias              | Deve listar tecnologias citadas nas vagas               | Validado  |
| Competências             | Deve apresentar competências técnicas e comportamentais | Validado  |
| Análise final            | Deve responder o que o mercado exige                    | Validado  |
| Rodapé                   | Deve apresentar disciplina, acadêmico e ano             | Validado  |

## Teste 5 - Responsividade

| Dispositivo/tamanho | Resultado esperado                                       | Status    |
| ------------------- | -------------------------------------------------------- | --------- |
| Desktop             | Layout deve aparecer em colunas quando aplicável         | Validado  |
| Notebook            | Conteúdo deve permanecer legível e organizado            | Validado  |
| Tablet              | Cards e colunas devem se adaptar ao tamanho da tela      | Validado  |
| Celular             | Conteúdo deve aparecer em coluna única quando necessário | Validado  |
| Menu mobile         | Navbar deve exibir botão de menu recolhido               | Validado  |

## Teste 6 - Acessibilidade básica

| Verificação           | Resultado esperado                                      | Status    |
| --------------------- | ------------------------------------------------------- | --------- |
| Idioma da página      | A tag `html` deve conter `lang="pt-BR"`                 | Validado  |
| Hierarquia de títulos | Deve existir um `h1` principal e subtítulos organizados | Validado  |
| Texto alternativo     | Imagens devem possuir atributo `alt`                    | Validado  |
| Links compreensíveis  | Links devem indicar claramente seu destino              | Validado  |
| Navegação por teclado | Menu e links devem ser acessíveis com teclado           | Validado  |
| Contraste visual      | Textos devem ser legíveis sobre o fundo                 | Pendente  |

## Teste 7 - Publicação no GitHub Pages

| Verificação                        | Resultado esperado                                      | Status    |
| ---------------------------------- | ------------------------------------------------------- | --------- |
| Repositório criado                 | Projeto deve estar disponível no GitHub                 | Validado  |
| GitHub Pages configurado           | Página deve estar publicada pela branch principal       | Pendente  |
| Página publicada abre corretamente | URL pública deve abrir a landing page                   | Pendente  |
| Arquivos estáticos carregam        | CSS, logo e favicon devem funcionar na versão publicada | Pendente  |
| Links internos funcionam           | Menu deve navegar corretamente na versão publicada      | Pendente  |
