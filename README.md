# Landing Page — Vanessa Silva Nails Designer

## Por que essa landing page?

Este projeto foi desenvolvido na primeira fase do curso de **Análise e Desenvolvimento de Sistemas (ADS)** da **Faculdade Municipal de Palhoça (FMP)**. O objetivo é oferecer uma landing page para minha mãe e seu estúdio de Nails Designer, facilitando o acesso às informações e o contato com suas clientes.

## Linguagens utilizadas

A landing page utiliza três tecnologias principais: **HTML, CSS e JavaScript**.

- **HTML (HyperText Markup Language):** estrutura o conteúdo da página, incluindo textos, títulos, imagens, botões, serviços, horários, localização e contatos.
- **CSS (Cascading Style Sheets):** define a aparência visual, como cores, fontes, espaçamentos, tamanhos, bordas, sombras, transições e organização dos elementos. Também adapta o layout a celulares, tablets e computadores.
- **JavaScript:** implementa funcionalidades dinâmicas, como links do WhatsApp com mensagens prontas, atualização automática do ano no rodapé, destaque do dia atual e indicação de estabelecimento aberto ou fechado.

## Principais tags HTML

O código utiliza tags semânticas para organizar o conteúdo:

- `<html>`: define o documento e o idioma `pt-BR`.
- `<head>`: reúne configurações, metadados, título e importações.
- `<title>`: define o título da aba do navegador.
- `<meta>`: configura a codificação, a visualização em dispositivos móveis e a descrição da página.
- `<link>`: importa fontes do Google Fonts e permite conexões antecipadas.
- `<style>`: contém as regras CSS.
- `<body>`: contém o conteúdo visível.
- `<header>`: apresenta a seção inicial.
- `<main>`: agrupa o conteúdo principal.
- `<section>`: separa áreas como serviços, trabalhos, horários, localização e contato.
- `<article>`: organiza os cartões individuais dos serviços.
- `<h1>`, `<h2>` e `<h3>`: estabelecem a hierarquia dos títulos.
- `<p>`: apresenta textos e descrições.
- `<a>`: cria links para WhatsApp, Instagram, e-mail e Google Maps.
- `<img>`: exibe fotografias.
- `<figure>`: agrupa imagens da galeria.
- `<address>`: apresenta o endereço do estabelecimento.
- `<footer>`: contém a identificação profissional e os direitos autorais.
- `<script>`: contém o JavaScript.

Essas tags contribuem para uma estrutura organizada, semântica e mais fácil de manter.

## Paleta de cores e identidade visual

A identidade visual utiliza cores suaves e delicadas, transmitindo beleza, cuidado, elegância e profissionalismo. As principais cores são definidas como variáveis CSS em `:root`, facilitando sua reutilização.

| Cor | Código HEX | Utilização |
|---|---|---|
| Rosa-claro | `#F6B1C2` | Botões e destaques |
| Rosa-escuro | `#D9738F` | Detalhes, ícones e destaques |
| Lavanda | `#DBE2FA` | Fundos e transições |
| Roxo-escuro | `#3B3148` | Textos principais |
| Cinza-arroxeado | `#6B6178` | Textos secundários e descrições |
| Branco | `#FFFFFF` | Cartões, botões e áreas de conteúdo |
| Branco levemente rosado | `#FDFBFE` | Fundo principal |
| Rosa muito suave | `#FDF0F4` | Fundo alternado dos cartões de serviços |
| Lavanda muito suave | `#F3F5FD` | Cartões, contatos e galeria |

O site também utiliza gradientes para criar transições suaves entre as cores e manter uma identidade visual consistente.

## Tipografia

O projeto importa duas fontes do Google Fonts:

- **Jost:** usada nos textos, descrições, botões e informações de contato. Tem um estilo moderno e facilita a leitura.
- **Grand Hotel:** usada no nome da profissional, em alguns títulos e na assinatura do rodapé. Seu estilo cursivo reforça a identidade delicada da página.

A combinação cria contraste entre os textos informativos e os elementos de destaque.

## Organização da página

A landing page está dividida em seções que ajudam o visitante a encontrar as informações:

1. **Seção inicial:** nome, especialidade, fotografia e botão de agendamento pelo WhatsApp.
2. **Serviços:** seis opções — alongamento de unha, esmaltação em gel, banho de gel, manicure, pedicure e spa dos pés. Cada serviço possui ícone, título, descrição e link de agendamento.
3. **Trabalhos realizados:** galeria de fotografias e botão para entrar em contato.
4. **Horários de atendimento:** apresenta os dias e períodos de funcionamento, destaca o dia atual e informa se o estabelecimento está aberto ou fechado.
5. **Localização:** exibe o endereço e um link para abrir o Google Maps.
6. **Contato:** reúne WhatsApp, Instagram e e-mail.
7. **Rodapé:** mostra a identificação profissional, a cidade e o ano dos direitos autorais, atualizado automaticamente.

Essa organização facilita a navegação e torna as informações mais acessíveis.

## Responsividade

O projeto utiliza técnicas de CSS responsivo para adaptar o layout à largura da tela. As **media queries** (`@media`) alteram a disposição dos elementos em diferentes tamanhos de dispositivo.

Por exemplo, a galeria passa de uma coluna para duas colunas a partir de 700 pixels. Os cartões de serviços também passam de uma coluna para duas e, em telas maiores, para três colunas.

O layout utiliza ainda **CSS Grid** e recursos como `clamp()`, `min()` e `aspect-ratio` para organizar elementos e controlar seus tamanhos. Isso melhora a experiência em celulares, tablets e computadores.

## Funcionalidades em JavaScript

O JavaScript adiciona funcionalidades dinâmicas:

- **Integração com o WhatsApp:** links com o atributo `data-wpp` recebem automaticamente o endereço de contato e uma mensagem pré-definida, que pode mencionar o serviço desejado.
- **Ano automático:** o rodapé é atualizado com o ano atual usando o objeto `Date`.
- **Destaque do dia:** a linha correspondente ao dia atual recebe uma classe CSS.
- **Status de atendimento:** o código compara o dia e o horário atuais com os horários definidos e exibe uma mensagem de aberto ou fechado.

Esses recursos tornam a página mais prática e reduzem a necessidade de atualizações manuais.

## Efeitos visuais e experiência do usuário

O CSS inclui botões com bordas arredondadas, sombras e transições. Ao passar o cursor sobre eles, a cor muda e o botão se desloca levemente, indicando que é interativo.

Os cartões alternam entre tons suaves de rosa e lavanda, e os ícones ajudam a identificar os serviços. Na seção inicial, gradientes e formas circulares desfocadas — chamadas de *blobs* — criam profundidade visual.

A página também oferece rolagem suave e destaque visual para elementos focados pelo teclado.

## Acessibilidade e boas práticas

O projeto inclui práticas positivas, como:

- Definição do idioma do documento (`pt-BR`).
- Uso de tags semânticas.
- Texto alternativo (`alt`) na fotografia principal.
- Uso de `aria-hidden` em elementos decorativos.
- Uso de `rel="noopener"` em links externos abertos em uma nova aba.
- Redução das transições para pessoas que configuraram preferência por movimento reduzido.

Alguns pontos podem ser melhorados: as imagens da galeria precisam de textos alternativos, o contraste de certos textos secundários pode ser revisado e os links de agendamento devem ser testados. Também é recomendável verificar o comportamento do status de atendimento em dispositivos com fusos horários diferentes.

## Objetivo e importância

O objetivo principal da landing page é apresentar os serviços da profissional Vanessa Silva, fortalecer sua identidade visual e facilitar o contato com potenciais clientes.

Ao reunir serviços, fotografias, horários, localização e canais de comunicação em um só lugar, o site funciona como uma vitrine digital. A integração com o WhatsApp reduz as etapas necessárias para solicitar um agendamento, enquanto a galeria permite que os visitantes conheçam exemplos do trabalho antes de entrar em contato.
