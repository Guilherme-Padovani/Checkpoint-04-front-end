# TRIVOLUNE — Landing Page de Produto

Projeto acadêmico de uma landing page para **TRIVOLUNE**, uma mochila urbana fictícia para estudo e viagem, desenvolvido em **HTML5 e CSS3**.

O tema foi adaptado para outro produto, mantendo a estrutura do [Figma — LP de Produto](https://www.figma.com/design/8FBssL4H9MtYhgABk4f4Ec/LP-de-produto?m=auto) e a tipografia Inter indicada na referência. Conforme a personalização solicitada para o projeto, a página utiliza uma **paleta própria em creme e verde**, diferente das cores do Style Guide original. O foco do trabalho é a responsividade e a organização do layout.

## Como visualizar

1. Extraia `landing-page-produto-trivolune.zip` com **Extrair Tudo**.
2. Abra a pasta `landing-page-produto` extraída.
3. Abra `index.html` em um navegador atualizado.

Mantenha `index.html`, `css` e `assets` na mesma organização de pastas. A implementação usa HTML e CSS, sem frameworks, JavaScript ou instalação de pacotes.

## Estrutura do projeto

```text
landing-page-produto/
├── index.html       # Estrutura e conteúdo da página
├── css/
│   └── style.css    # Estilização e media queries
├── assets/          # Imagens, ícones e fontes do projeto
│   ├── mochila-trivolune.png
│   ├── organizacao-trivolune.png
│   └── fonts/
│       └── OFL.txt  # Licença da fonte Inter
├── README.md
└── .gitignore
```

## Organização da página

- Cabeçalho com marca e navegação.
- Apresentação principal do produto (hero).
- Seção sobre a mochila.
- Cinco cartões de funcionalidades.
- Três opções de compra.
- Chamada final para conhecer as opções.
- Rodapé com navegação e informações complementares.

O layout utiliza elementos semânticos, CSS separado do HTML, Flexbox, Grid e media queries para adaptar imagens, textos e seções a desktop, tablet e celular. Os pontos de adaptação são `48rem` e `64rem`. A identidade visual está documentada em `STYLE_GUIDE.md`.

## Conferência antes da entrega

O projeto foi testado no Chrome pela prévia local nas larguras de **320, 375, 390, 767, 768, 1023, 1024 e 1440 pixels**, sem rolagem horizontal ou transbordamento dos textos visíveis. Os três botões de escolha abrem avisos demonstrativos e permitem retornar às opções.

Abra a página e redimensione a janela, ou use o modo de dispositivo nas ferramentas do navegador (`F12`). Confira, por exemplo, larguras de 320, 375, 768, 1024 e 1440 pixels. Observe se os textos permanecem legíveis, as imagens cabem nos espaços e não há sobreposição ou rolagem horizontal. Verifique também os links de navegação e o carregamento dos arquivos após extrair o ZIP.

## Referências e créditos

- Referência de estrutura, organização e tipografia: [Figma — LP de Produto](https://www.figma.com/design/8FBssL4H9MtYhgABk4f4Ec/LP-de-produto?m=auto), incluindo a aba **Style Guide**. As cores foram adaptadas para a identidade do produto.
- Material de referência original: [Rocketseat Education — lp-de-produto](https://github.com/rocketseat-education/lp-de-produto).
- Tipografia: [Inter](https://rsms.me/inter/), em arquivos WOFF2 locais. Sua licença **SIL Open Font License (OFL)** acompanha os arquivos em `assets/fonts/OFL.txt`.
- Imagens da mochila: geradas especificamente para ilustrar o conceito deste projeto, com produto verde-musgo e fundo claro.

**TRIVOLUNE é um nome inventado para esta atividade.** O produto, as características comerciais, os preços e as opções de compra são ilustrativos para a atividade acadêmica. A página não representa uma loja em operação nem realiza vendas.
