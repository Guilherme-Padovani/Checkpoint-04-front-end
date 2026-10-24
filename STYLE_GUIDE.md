# Style Guide — TRIVOLUNE

TRIVOLUNE é um nome criado para esta atividade, aplicado a uma mochila urbana fictícia para estudo e viagem.

## Referência e adaptação

A estrutura segue o [Figma — LP de Produto](https://www.figma.com/design/8FBssL4H9MtYhgABk4f4Ec/LP-de-produto?m=auto), com cabeçalho, hero, apresentação, cinco funcionalidades, três kits, chamada final (CTA) e rodapé.

Este guia registra a identidade personalizada do projeto. A paleta creme e verde atende à solicitação de usar cores diferentes do modelo; **não é a paleta original do Style Guide fornecido pelo docente**. A tipografia Inter foi preservada.

## Paleta

| Uso no CSS | Cor |
| --- | --- |
| Fundo — `--background` | `#F5F2E9` |
| Superfície — `--surface` | `#E9EDE5` |
| Bordas — `--stroke` | `#C9D4C7` |
| Texto principal — `--text` | `#173A32` |
| Texto secundário — `--muted` | `#52665D` |
| Verde principal — `--primary` | `#28634B` |
| Verde complementar — `--secondary` | `#81AA74` |
| Gradiente, da esquerda para a direita | `#DBE9C2` → `#ADD2B9` |

## Tipografia

- Família: **Inter**, variável de peso **100 a 900**, em arquivos WOFF2 locais em `assets/fonts/`.
- Licença: **SIL Open Font License**, incluída em `assets/fonts/OFL.txt`.
- Alternativas: Arial e sans-serif.
- Títulos: peso 800, entrelinha 1,2 e espaçamento entre letras de −0,04em.
- Corpo: 16px, entrelinha 1,6.

Escala geral de `h1 / h2 / h3 / corpo`, considerando 1rem = 16px:

| Faixa | Escala em pixels |
| --- | --- |
| Mobile, abaixo de 48rem | 40 / 24 / 20 / 16 |
| Tablet, a partir de 48rem | 56 / 40 / 28 / 16 |
| Desktop, a partir de 64rem | 64 / 48 / 32 / 16 |

Cartões, preços e navegação possuem ajustes específicos no CSS para respeitar seu espaço disponível.

## Layout e imagens

- Breakpoints: **48rem (768px)** e **64rem (1024px)**.
- Containers fluidos, com largura máxima de 80rem; Flexbox e Grid reorganizam as seções.
- Cartões com cantos arredondados de 1,5rem; botões com 0,5rem.
- Mochila verde-musgo sobre fundo claro, em imagens geradas para o conceito: `mochila-trivolune.png` e `organizacao-trivolune.png`.
- Produto, kits e preços são ilustrativos e destinam-se à demonstração acadêmica.
