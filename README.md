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
animes-bootstrap/
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

- [Esboço para computador](animes-bootstrap/esbocos/esboco-computador.svg)
- [Esboço para celular](animes-bootstrap/esbocos/esboco-celular.svg)

## Como rodar

Não é preciso instalar nada. Basta clonar ou baixar o repositório e abrir o arquivo `animes-bootstrap/index.html` no navegador.

Se preferir, use a extensão **Live Server** do VS Code para recarregar a página automaticamente a cada alteração.

> É preciso estar conectado à internet para carregar as fontes do Google Fonts e algumas imagens da página de favoritos, que vêm de sites externos.

## Próximos passos

- Criar uma barra de pesquisa de animes com JavaScript

## Créditos

As imagens dos animes pertencem aos seus respectivos estúdios e detentores de direitos e são usadas aqui apenas para fins educacionais.
