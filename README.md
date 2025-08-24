# css-book

Folha de estilos e HTML de exemplo para um livro (EPUB/HTML), seguindo classes semânticas e separação de estilos.

## O que foi adicionado
- `book-sample.html`: exemplo mínimo e semântico de uma página de Parte + Capítulo + Seções, usando classes padronizadas.
- `style.css`: folha de estilos externa com as cores e hierarquia definidas.

## Cores (fornecidas)
- Azul (badge capítulo): `#3b55a2`
- Cinza (seções/subseções): `#80818e`
- Título de Partes/Capítulos: `#75c9dc`
- Números: branco

## Estrutura de classes
- `.part` (com `.part__label`, `.part__number`, `.part__title`)
- `.chapter` (com `.chapter__badge`, `.chapter__number`, `.chapter__title`)
- `.section` (com `.section__title`) e `.subsection__title`
- `.figure` (com `.figure__placeholder`, `.figure__caption`) e `.table` (com `.table__caption`)

## Como usar
Abra `book-sample.html` no navegador/preview. Substitua o texto dummy pelo conteúdo real. Imagens e figuras podem ser inseridas no lugar do elemento `.figure__placeholder`.

Caso use EPUB, mantenha os estilos o mais plano possível (sem dependências externas) e use caminhos relativos para fontes/imagens.
