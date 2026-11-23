# Animes & Devs

Um guia de animes da temporada feito por dois estudantes de TI que também são fãs de anime.

Projeto desenvolvido para a disciplina **Desenvolvimento para Internet** do curso de **Tecnologia em Análise e Desenvolvimento de Sistemas** da **Uninove** (1º semestre), nas aulas do professor Felipe.

## Autores

- **André Luiz**
- **Thuanne**

## Sobre o projeto

O **Animes & Devs** reúne os destaques da temporada, os animes favoritos dos desenvolvedores e links para assistir cada um deles. Escolhemos o tema por ser uma das nossas maiores paixões: a gente aprende mais rápido quando constrói algo de que gosta.

Escrevemos a estrutura HTML do site à mão, com base nas aulas, em cursos da Alura e em vídeos do YouTube. Usamos inteligência artificial como apoio para tirar dúvidas e aprender alguns efeitos (como o fade do carrossel e a integração da paleta de cores com o Bootstrap). A ideia, os textos, a estrutura e a escolha do tema, da paleta e das fontes são nossos.

## Páginas

| Página | Arquivo | Conteúdo |
| --- | --- | --- |
| Início | `index.html` | Carrossel com os destaques da temporada, apresentação do projeto e cards com sinopse de cada anime |
| Sobre | `sobre.html` | Quem somos, como foi fazer o projeto e perguntas frequentes (accordion) |
| Favoritos dos Devs | `favsdev.html` | Nossas recomendações pessoais, com link para assistir |
| Outros projetos | `outros-projetos.html` | Projetos anteriores da disciplina |
| Onde assistir | `ondeassistir.html` | Plataformas de streaming onde dá para assistir os animes |

## Tecnologias e conceitos

- **HTML5** semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** com variáveis no `:root` para a paleta de cores
- **Bootstrap 5.3.8** (arquivos locais na pasta `vendor/`): grid, navbar, botões, cards, carrossel e accordion
- **Mobile first** e **media queries**: o menu vira o botão ☰ em telas menores que 992px
- **Flexbox**
- **Acessibilidade**: textos alternativos nas imagens, `aria-label`, textos para leitores de tela (`visually-hidden`) e respeito a `prefers-reduced-motion`
- **Google Fonts**: Fredoka e Luckiest Guy

## Estrutura de pastas

```
Atividade4/
├── index.html
├── sobre.html
├── favsdev.html
├── outros-projetos.html
├── ondeassistir.html
├── estilo.css          # nosso CSS, carregado depois do Bootstrap
├── imagens/            # imagens dos animes e mascote
├── esbocos/            # esboços do site para computador e celular
└── vendor/             # Bootstrap (CSS e JS)
```

## Esboços

Antes de implementar, a Aula 13 pede dois esboços do site, um para computador e outro para celular, com as seis áreas da página, a posição das imagens e a função de cada controle:

- [Esboço para computador](Atividade4/esbocos/esboco-computador.svg)
- [Esboço para celular](Atividade4/esbocos/esboco-celular.svg)

## Registro dos componentes

Uma frase para cada componente do Bootstrap usado no site, como pede a atividade:

- **Navbar:** Usei a navbar no topo de todas as páginas para levar às páginas Sobre, Outros projetos, Favoritos dos Devs e Onde assistir. Adaptei as cores (fundo escuro, linha rosa embaixo e logo rosa com sombra ciano) e o sublinhado da página atual, e testei no celular o botão ☰ abrindo e fechando o menu.
- **Buttons:** Usei buttons na página inicial ("Ver destaques" e "Ver os favoritos dos Devs") para levar o visitante aos cards e à página de favoritos. Adaptei o btn-primary para o rosa neon do site, com um rosa mais claro ao passar o mouse, e testei se cada botão leva ao lugar certo.
- **Cards:** Usei cards em Destaques da Temporada, Favoritos dos Devs, Onde assistir e Outros projetos para mostrar cada item com imagem, título e link. Adaptei a borda em degradê rosa e ciano, a imagem em 16:9 e o movimento ao passar o mouse, e testei a grade redimensionando a janela (1 coluna no celular, 2 no tablet e 3 no computador).
- **Carousel:** Usei o carousel na página inicial para mostrar 6 animes da temporada com legenda. Adaptei a transição para fade, o degradê escuro atrás da legenda e as setas brancas, sem avanço automático, e testei várias vezes as setas e as barrinhas de navegação.
- **Accordion:** Usei o accordion na página Sobre para as perguntas frequentes. Adaptei as cores da pergunta aberta (fundo roxo e texto rosa) e deixei só uma resposta aberta por vez, e testei abrir e fechar as 7 perguntas.

## Como rodar

Não é preciso instalar nada. Basta clonar ou baixar o repositório e abrir o arquivo `Atividade4/index.html` no navegador.

Se preferir, use a extensão **Live Server** do VS Code para recarregar a página automaticamente a cada alteração.

> É preciso estar conectado à internet para carregar as fontes do Google Fonts e algumas imagens da página de favoritos, que vêm de sites externos.

## Próximos passos

- Criar uma barra de pesquisa de animes com JavaScript

## Créditos

As imagens dos animes pertencem aos seus respectivos estúdios e detentores de direitos e são usadas aqui apenas para fins educacionais.
