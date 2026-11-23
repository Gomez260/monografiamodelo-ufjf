# Migração do TCC para o modelo de monografia UFJF

Este pacote foi montado a partir do `main.tex` e da pasta `Graphics/` do TCC original e preparado para usar a classe `monografia` do repositório `monografiamodelo-ufjf`.

## Arquivos
- `main.tex`: documento principal, pacotes, pré-texto, listas, abreviações e inclusões.
- `pretexto.tex`: título, autoria, curso, instituição e orientador.
- `capitulos/`: texto original dividido em capítulos.
- `Graphics/`: imagens extraídas do ZIP original, sem renomear.
- `hifenizacao.tex`: arquivo do template (criar/usar a versão existente no template).

## Como aplicar no repositório do template
1. Copie `main.tex`, `pretexto.tex`, `capitulos/` e `Graphics/` para a raiz do repositório `monografiamodelo-ufjf`.
2. Mantenha `monografia.cls`, `hifenizacao.tex` e demais arquivos de classe do template.
3. Compile `main.tex` (não o `modelo.tex` demonstrativo).
4. Revise a data de defesa no `pretexto.tex` (dia e mês estão `XX` porque ainda não foram informados).
5. Confira a compilação e revise a paginação, legendas, listas, citações e referências.

## Observações
- O conteúdo dos capítulos e a bibliografia foram preservados, com a conversão de `section/subsection/subsubsection` para a hierarquia de capítulos/seções do modelo.
- Os dois blocos finais de gráficos foram mantidos como apêndices.
- Os campos da banca não foram inventados.
- Este pacote é um overlay/migração de conteúdo; não contém `monografia.cls`, que permanece no repositório-template original.
